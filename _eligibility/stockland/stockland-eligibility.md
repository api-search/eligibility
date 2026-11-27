---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Membership is optional, free and open to all Australian residents aged 15 years and over.
  minimum_age:
    text: Membership is optional, free and open to all Australian residents aged 15 years and over.
    value: '15'
  restricted_uses:
  - summary: Illegal or abusive activity
    text: engage or make attempts to engage in any kind of illegal, criminal or tortious activity whatsoever through the use (whether direct or indirect) of the Website or Third Party Websites
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
name: Stockland
provenance_date: '2026-11-10'
provider_name: Stockland
provider_slug: stockland
slug: stockland-eligibility
source_date: '2026-11-10'
source_filename: stockland-eligibility.yml
source_heading: Eligibility
source_page: https://www.stockland.com.au/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stockland\naid: stockland\nurl: https://www.stockland.com.au/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Membership is optional, free and open to all Australian residents aged 15 years and over.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or abusive activity\n  text: engage or make attempts to engage in any kind of illegal, criminal or tortious activity whatsoever through\n    the use (whether direct or indirect) of the Website or Third Party Websites\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '15'\n  text: Membership is optional, free and open to all Australian residents aged 15 years and over.\n"
source_yaml_url: https://artifacts.apis.io/stockland/eligibility/stockland-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Stockland's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Property Development
- Retail
- Logistics
- Residential
- Australia
---
