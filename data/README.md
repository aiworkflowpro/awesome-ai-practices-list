# Data guide

All files are UTF-8 JSON Lines, one object per line. Dates are ISO 8601 with a UTC offset. Empty files are valid empty collections.

## posts.jsonl

`id` is the stable original post ID; `url` links to its author on X; `siteUrl` locates it in a daily archive. `author` contains name and handle. `topic`, `week`, `publishedAt`, `tools`, `versions` and `flags` describe collected metadata. `summary` describes these attributes without reproducing the post. A missing tool tag is not evidence that no tool was used.

## weekly.jsonl and monthly.jsonl

`url` identifies the edition; `kind`, `period` and `topic` form its stable identity. `title`, `summary`, `changes`, `tryNext` and `watch` contain the editorial text. Each sentence contains `sourceIds`, resolved by `sources` with an ID, author and URL. Monthly sources are approved weekly editions. `firstPublishedAt` stays stable across revisions; `updatedAt` records the last substantive change.

Do not assume that an edition was published for every topic or period. Original-source claims remain attributed and are not independent tests. See the [license](../LICENSE) for reuse and the rights of third-party authors.
