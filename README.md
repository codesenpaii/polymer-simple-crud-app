## Setup NowDB

Fill `src/polymer-simple-crud-app/data/config.json` with your NowDB API credential. Get it on [nowdb](http://nowdb.net).

```json
{
  "token"     : "your_token",
  "project"   : "your_project_name",
  "collection": "your_collection_name",
  "appid"     : "your_app_id"
}
```

## Setup Collection

Create collection with 3 type of fields: id, quote and quotee. Example:

```json
[
  {
    "quotee":"Linus Torvalds",
    "quote":"Talk is cheap. Show me the code.",
    "id":"5a33c8371f6d04d135bb9c7c"
  },
  {
    "quote":"Programs must be written for people to read, and only incidentally for machines to execute.",
    "quotee":"Harold Abelson",
    "id":"5a33dd311f6d045536bb9ca8"
  }
]
```

## Install

Just do `bower install` then `polymer serve`

Read nowdb v2 api [documentation](http://doc.nowdb.net/docs?page=v2_all) for complete understanding of the application flow.
