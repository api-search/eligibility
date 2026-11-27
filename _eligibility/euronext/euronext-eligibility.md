---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for jurisdictions where contrary to law
    text: The Euronext Website is not directed at or intended for publication or distribution to any person in any jurisdiction where doing so would result in contravention of any applicable laws or regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Euronext
provenance_date: '2026-11-09'
provider_name: Euronext
provider_slug: euronext
slug: euronext-eligibility
source_date: '2026-11-09'
source_filename: euronext-eligibility.yml
source_heading: Eligibility
source_page: https://www.euronext.com/en/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Euronext\naid: euronext\nurl: https://www.euronext.com/en/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for jurisdictions where contrary to law\n  text: The Euronext Website is not directed at or intended for publication or distribution to any person in any\n    jurisdiction where doing so would result in contravention of any applicable laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/euronext/eligibility/euronext-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Euronext's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Stocks
- Exchange
- Real-Time
- Historical Data
- Indices
- Reference Data
- Derivatives
- Regulatory Reporting
---
