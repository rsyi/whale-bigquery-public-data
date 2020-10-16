<p align="center"><img src="whale-bigquery-logo.png" width="350"/></p>

# Whale Demo Instance: Bigquery Public Data
This is a fully-functioning demo instance of the [whale data catalog](http://github.com/dataframehq/whale), actively scraping data from Bigquery's public project `bigquery-public-data` using github actions.

To test out this repo with your own local installation of whale (i.e. to emulate what it'd be like to set up whale on github for your own team), [install whale](https://docs.whale.cx/), then run the following commands and follow the prompts (if already have a `~/.whale` directory, move it or delete it with `rm -rf ~/.whale` or the clone won't work):

```
git clone https://github.com/dataframehq/whale-bigquery-public-data ~/.whale
wh git-enable
wh schedule
```

For more information on how to set this up for your own warehouse, see the [docs](https://docs.whale.cx/setup/getting-started-for-teams).
