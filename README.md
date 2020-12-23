<p align="center"><img src="whale-bigquery-logo.png" width="350"/></p>

# Whale Demo Instance: Bigquery Public Data
This is a fully-functioning demo instance of the [whale data catalog](http://github.com/dataframehq/whale), actively scraping data from Bigquery's public project `bigquery-public-data` using github actions.

To test out this repo with your own local installation of whale (i.e. to emulate what it'd be like to set up whale on github for your own team), clone the repo to your `~/.whale` directory (if you already have a `~/.whale` directory, move it or delete it with `rm -rf ~/.whale` or the clone won't work):

```
git clone https://github.com/dataframehq/whale-bigquery-public-data ~/.whale
```

Then [install whale](https://docs.whale.cx/) and run the following commands, following the prompts:

```
wh git-enable
wh schedule
```

At this point, if you run `wh pull`, it should run a `git pull --autostash --rebase` against this repo (meaning any locally scheduled cron jobs will simply pull down fresh metadata from this repo, rather than scraping directly from Bigquery).

For more information on how to set this up for your own warehouse, see the [docs](https://docs.whale.cx/setup/getting-started-for-teams).

## FAQ

### Why doesn't `wh.pull()` work locally?
While `wh pull` (the CLI hook) will check for a flag in `wh config` and act appropriately (sourcing from github if `is_git_etl_enabled` is True, and from the connections in `wh connections` if not), `wh.pull()` (the python hook) performs no such check. This is by design, to ensure the remote repository's associated CI/CD pipelines to pull down data directly from the metadata source, by default (we suspect most people do not want to refresh metadata using the python client, but feel free to open an issue if you disagree).

Locally, this will fail, unless you modify the `key_path` value specified in `wh connections` to some credentials you have stored locally. If you choose to do this, ensure you have the following permissions enabled in the associated service account: BigQuery Data Viewer, BigQuery Job User, BigQuery Metadata Viewer.
