# Every Number sample exports

Six sets of spreadsheet exports that look like what teams download every week, three weekly exports each (October 4, 11 and 18, 2026). Use them to try a dashboard tool, test a CSV or Excel parser, or see how [Every Number](https://everynumber.app) turns a file into a dashboard where every number has a receipt.

All values are made up. There are no real people, customers or companies in these files.

Like real exports, they are a little messy on purpose: title rows above the header, totals rows at the bottom, test accounts, test orders, spam and duplicates. A good dashboard should count those out and say so.

| Folder | What it looks like | Files | Rows to leave out |
|---|---|---|---|
| [`signups/`](signups) | A sign-up export from a product database: plans, sources, and who finished setup | CSV | Our own test accounts |
| [`orders/`](orders) | A month-to-date order export from an online shop, with a title row and a totals row | XLSX | Test orders |
| [`tickets/`](tickets) | A ticket export from a help desk, twelve weeks of tickets | CSV | Spam, merged duplicates |
| [`hiring/`](hiring) | A candidate export from an applicant tracking system, everyone who applied in the last 12 weeks | XLSX | Duplicate applications |
| [`projects/`](projects) | A PMO status spreadsheet for 24 projects, with archived projects and a totals row | XLSX | Archived projects, the totals row |
| [`ads/`](ads) | Eight weeks of daily campaign results for three clients, from an ads platform | CSV | Test campaigns |

[`templates/`](templates) has two templates with example rows: a chief of staff weekly report and a metrics dictionary (definition, calculation, source, filters, rows left out, owner).

## Turn one into a dashboard

1. Download any file, for example [`orders/orders-month-to-date-2026-10-18.xlsx`](orders/orders-month-to-date-2026-10-18.xlsx).
2. Drop it at [everynumber.app/try](https://everynumber.app/try). No account is needed, and the result is deleted after 24 hours unless you save it.
3. Click any number to see its receipt: the definition, the rows used and the rows left out.

With a free team account (30 days), add the next week's file to the same dashboard and see what changed.

## License

The files and this README are released under [CC0 1.0](LICENSE). Use them for anything, no credit needed.
