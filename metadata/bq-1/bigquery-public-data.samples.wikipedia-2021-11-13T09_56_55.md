# `samples.wikipedia-2021-11-13T09_56_55`
`bq-1` | `bigquery-public-data`

## Column details
* [STRING]    `title`
  - The title of the page, as displayed on the page (not in the URL). Always starts with a capital letter and may begin with a namespace (e.g. "Talk:", "User:", "User Talk:", ... )
* [INTEGER]   `id`
  - A unique ID for the article that was revised. These correspond to the order in which articles were created, except for the first several thousand IDs, which are issued in alphabetical order.
* [STRING]    `language`
  - Empty in the current dataset.
* [INTEGER]   `wp_namespace`
  - Wikipedia segments its pages into namespaces (e.g. "Talk", "User", etc.)

MEDIA = 202; // =-2 in WP XML, but these values must be >0
SPECIAL = 201; // =-1 in WP XML, but these values must be >0
MAIN = 0;
TALK = 1;
USER = 2;
USER_TALK = 3;
WIKIPEDIA = 4;
WIKIPEDIA_TALK = 5;
IMAGE  = 6;  // Has since been renamed to "File" in WP XML.
IMAGE_TALK = 7;  // Equivalent to "File talk".
MEDIAWIKI = 8;
MEDIAWIKI_TALK = 9;
TEMPLATE = 10;
TEMPLATE_TALK = 11;
HELP = 12;
HELP_TALK = 13;
CATEGORY = 14;
CATEGORY_TALK = 15;
PORTAL = 100;
PORTAL_TALK = 101;
WIKIPROJECT = 102;
WIKIPROJECT_TALK = 103;
REFERENCE = 104;
REFERENCE_TALK = 105;
BOOK = 108;
BOOK_TALK = 109;
* [BOOLEAN]   `is_redirect`
  - Versions later than ca. 200908 may have a redirection marker in the XML.
* [INTEGER]   `revision_id`
  - These are unique across all revisions to all pages in a particular language and increase with time. Sorting the revisions to a page by revision_id will yield them in chronological order.
* [STRING]    `contributor_ip`
  - Typically, either _ip or (_id and _username) will be set. IP information is unavailable for edits from registered accounts. A (very) small fraction of edits have neither _ip or (_id and _username). They show up on Wikipedia as "(Username or IP removed)".
* [INTEGER]   `contributor_id`
  - Typically, either (_id and _username) or _ip will be set. A (very) small fraction of edits have neither _ip or (_id and _username). They show up on Wikipedia as "(Username or IP removed)".
* [STRING]    `contributor_username`
  - Typically, either (_id and _username) or _ip will be set. A (very) small fraction of edits have neither _ip or (_id and _username). They show up on Wikipedia as "(Username or IP removed)".
* [INTEGER]   `timestamp`
  - In Unix time, seconds since epoch.
* [BOOLEAN]   `is_minor`
  - Corresponds to the "Minor Edit" checkbox on Wikipedia's edit page.
* [BOOLEAN]   `is_bot`
  - A special flag that some of Wikipedia's more active bots voluntarily set.
* [INTEGER]   `reversion_id`
  - If this edit is a reversion to a previous edit, this field records the revision_id that was reverted to. If the same article text occurred multiple times, then this will point to the earliest revision. Only revisions with greater than fifty characters are considered for this field. This is to avoid labeling multiple blankings as reversions.
* [STRING]    `comment`
  - Optional user-supplied description of the edit. Section edits are, by default, prefixed with "/* Section Name */ ".
* [INTEGER]   `num_characters`
  - The length of the article after the revision was applied.

-------------------------------------------------------------------------------
*Do not make edits above this line.*
