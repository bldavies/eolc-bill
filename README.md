# eolc-bill

`votes.csv` contains data on New Zealand MPs' votes on the first, second and third readings of the [End of Life Choice Bill](https://www.parliament.nz/en/pb/bills-and-laws/bills-proposed-laws/document/BILL_74307/end-of-life-choice-bill/).
These data are derived from articles published [here](https://www.nzherald.co.nz/nz/news/article.cfm?c_id=1&objectid=12244261) and [here](https://www.nzherald.co.nz/nz/news/article.cfm?c_id=1&objectid=12285000) by the NZ Herald.

## Data dictionary

Variable | Type | Description
--- | --- | ---
`name` | str | MP name
`party` | str | MP party affiliation
`electorate` | str | MP electorate
`leader` | int | Binary indicator for whether MP leads their party
`first`, `second`, `third` | int | Binary indicator for whether MP supported bill on its first, second, and third readings

## License

CC0
