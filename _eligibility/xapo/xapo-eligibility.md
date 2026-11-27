---
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: no offer or invitation is made to any US persons (being residents of the United States of America or partnerships or corporations organised under the laws of the United States of America or any state, territory or possession thereof), who are excluded from the services offered in this Website.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or unlawful use
    text: use the Website for any fraudulent or unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Xapo
provenance_date: '2026-11-10'
provider_name: Xapo
provider_slug: xapo
slug: xapo-eligibility
source_date: '2026-11-10'
source_filename: xapo-eligibility.yml
source_heading: Eligibility
source_page: https://legal.xapobank.com/misc/website-terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xapo\naid: xapo\nurl: https://legal.xapobank.com/misc/website-terms-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  text: no offer or invitation is made to any US persons (being residents of the United States of America or partnerships\n    or corporations organised under the laws of the United States of America or any state, territory or possession\n    thereof), who are excluded from the services offered in this Website.\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent or unlawful use\n  text: use the Website for any fraudulent or unlawful purpose\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xapo/eligibility/xapo-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Xapo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Bitcoin
- Banking
- Custody
- Payments
- Wealth Management
- Fintech
---
