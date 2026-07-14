# decent.church API Documentation

The static JSON API provides programmatic access to decent.church articles, series, topics, feeds, and site metadata.

## Endpoints

### All Articles
**Endpoint:** `/api/guides.json`

Returns every published article with title, URL, description, path level, tags, estimated reading time, optional series metadata, image, and content length.

### Series
**Endpoint:** `/api/series.json`

Returns multi-part article series such as finding a church family, finding faith, discerning purpose, and loving God and neighbor.

### Topics
**Endpoint:** `/api/topics.json`

Returns article tags and the articles associated with each topic.

### Site Index
**Endpoint:** `/index.json`

Returns high-level site metadata, statistics, endpoint links, and navigation.

### Feed
**Endpoint:** `/feed.xml`

Standard RSS/Atom feed of latest articles.

## Content Notes

Articles are generated from `topics.json` with an NIV-based, Scripture-grounded prompt. Content should welcome readers across Judeo-Christian values, center the commands to love God and love neighbor, and avoid emojis.

## Attribution

When reusing content, credit "decent.church" and link to the original article URL.

Example citation:

`[Article Title], decent.church (https://decent.church/guides/[article-slug]/)`
