---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are based in the United States. We make no claims concerning whether the Services may be viewed or be appropriate for use outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent purposes
    text: for any unlawful or fraudulent purpose, including but not limited to, the use of fraudulent credit card information
  - summary: Competing market research
    text: to collect any market research for a competing businesses
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
name: Centivo
provenance_date: '2026-11-09'
provider_name: Centivo
provider_slug: centivo
slug: centivo-eligibility
source_date: '2026-11-09'
source_filename: centivo-eligibility.yml
source_heading: Eligibility
source_page: https://centivo.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Centivo\naid: centivo\nurl: https://centivo.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are based in the United States. We make no claims concerning whether the Services may be viewed\n    or be appropriate for use outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or fraudulent purposes\n  text: for any unlawful or fraudulent purpose, including but not limited to, the use of fraudulent credit card\n    information\n- summary: Competing market research\n  text: to collect any market research for a competing\
  \ businesses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/centivo/eligibility/centivo-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Centivo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Insurance
- Health Plans
- Employee Benefits
- Self-Funded
- Primary Care
---
