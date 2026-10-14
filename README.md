# UK public tenders by trade (open data)

Live, open UK public-sector tenders grouped into 20 trades, rebuilt from the official Find a Tender and Contracts Finder feeds. Data through **2026-10-13**. Each row links to the official notice.

Use it to spot contracts worth bidding for without signing up to a monthly alert service. The CSVs are plain UTF-8 with one notice per row (title, buyer, region, value, deadline, procedure, SME-suitable flag, source, published date, notice URL).

| Trade | Open notices | Data | Browse |
|---|---|---|---|
| [Cleaning](trades/cleaning.md) | 74 | [CSV](data/cleaning.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/cleaning/?utm_source=github) |
| [Grounds maintenance](trades/grounds-maintenance.md) | 60 | [CSV](data/grounds-maintenance.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/grounds-maintenance/?utm_source=github) |
| [Roofing](trades/roofing.md) | 26 | [CSV](data/roofing.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/roofing/?utm_source=github) |
| [Security services](trades/security.md) | 15 | [CSV](data/security.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/security/?utm_source=github) |
| [Catering](trades/catering.md) | 36 | [CSV](data/catering.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/catering/?utm_source=github) |
| [IT support and managed services](trades/it-support.md) | 23 | [CSV](data/it-support.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/it-support/?utm_source=github) |
| [Software and SaaS](trades/software.md) | 112 | [CSV](data/software.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/software/?utm_source=github) |
| [Construction and building works](trades/construction.md) | 428 | [CSV](data/construction.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/construction/?utm_source=github) |
| [Electrical contracting](trades/electrical.md) | 110 | [CSV](data/electrical.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/electrical/?utm_source=github) |
| [Plumbing, heating and gas](trades/plumbing-heating.md) | 62 | [CSV](data/plumbing-heating.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/plumbing-heating/?utm_source=github) |
| [Waste management](trades/waste-management.md) | 23 | [CSV](data/waste-management.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/waste-management/?utm_source=github) |
| [Transport and fleet](trades/transport.md) | 110 | [CSV](data/transport.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/transport/?utm_source=github) |
| [Consultancy](trades/consultancy.md) | 211 | [CSV](data/consultancy.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/consultancy/?utm_source=github) |
| [Marketing and communications](trades/marketing-design.md) | 54 | [CSV](data/marketing-design.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/marketing-design/?utm_source=github) |
| [Training and education services](trades/training.md) | 180 | [CSV](data/training.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/training/?utm_source=github) |
| [Recruitment and staffing](trades/recruitment.md) | 39 | [CSV](data/recruitment.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/recruitment/?utm_source=github) |
| [Facilities management](trades/facilities-management.md) | 163 | [CSV](data/facilities-management.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/facilities-management/?utm_source=github) |
| [Printing](trades/printing.md) | 25 | [CSV](data/printing.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/printing/?utm_source=github) |
| [Legal services](trades/legal-services.md) | 9 | [CSV](data/legal-services.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/legal-services/?utm_source=github) |
| [Care and support services](trades/care-services.md) | 44 | [CSV](data/care-services.csv) | [page](https://sme-free-tools.pages.dev/uk-tenders/care-services/?utm_source=github) |

## Want it filtered for your business?

The [UK tender keyword report](https://sme-free-tools.pages.dev/tender-keyword-report/?utm_source=github&utm_campaign=open-data) (£25 one-off, a product of GPT Shop Ltd) gives you every open match for your own keywords and region, buyer contact details where the buyer published them, upcoming pipeline notices, and recent awards showing who won and for how much, as a CSV and a PDF within 24 hours on a weekday. Grounds-maintenance firms can get the dedicated [green-space tender pack](https://greenspacetenderbrief.co.uk/pack/?utm_source=github).

## How this is built

Notices are ingested daily from the public OCDS APIs of [Find a Tender](https://www.find-tender.service.gov.uk/) and [Contracts Finder](https://www.contractsfinder.service.gov.uk/), deduplicated, filtered to notices still open, and matched to each trade by keyword. Always confirm details on the official notice before bidding. Not affiliated with the UK Government.

## Licence

Contains public sector information licensed under the Open Government Licence v3.0 (Find a Tender Service and Contracts Finder, Crown copyright). Repository code and layout: MIT. Compiled by GPT Shop Ltd (UK company no. 15766335). Contact: gptshop@mail.grokbot.com.
