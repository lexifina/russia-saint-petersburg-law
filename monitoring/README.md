<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Saint Petersburg only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 05:50 UTC, Saint Petersburg: Official Internet Portal of Legal Information (region78): 12 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Saint Petersburg: Official Internet Portal of Legal Information (region78)](http://publication.pravo.gov.ru/documents/block/region78) | `zakony-<year>/` | daily | 2026-11-27 05:50 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 05:50](checks/2026-11.md#ru-pravo-saint-petersburg-20261127t055001z) | pravo-saint-petersburg | 12 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 05:54](checks/2026-11.md#ru-pravo-saint-petersburg-20261126t055439z) | pravo-saint-petersburg | 12 | 3 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-saint-petersburg-law/compare/2983ed9310ca...67445a242eb2) |
| [2026-11-25 06:30](checks/2026-11.md#ru-pravo-saint-petersburg-20261125t063010z) | pravo-saint-petersburg | 12 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:39](checks/2026-11.md#ru-pravo-saint-petersburg-20261124t143941z) | pravo-saint-petersburg | 12 | 16 | 0 | 0 | 0 (0) | changes found | [5](https://github.com/lexifina/russia-saint-petersburg-law/compare/572bcdb36a7a...2cfac9442231) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
