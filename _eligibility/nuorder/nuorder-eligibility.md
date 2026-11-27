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
  - summary: Illegal or fraudulent activity
    text: NuORDER may suspend or terminate your access or use of the Services immediately and without notice, if you use the Service to (i) engage in an illegal or fraudulent activity
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
name: NuORDER
provenance_date: '2026-11-10'
provider_name: NuORDER
provider_slug: nuorder
slug: nuorder-eligibility
source_date: '2026-11-10'
source_filename: nuorder-eligibility.yml
source_heading: Eligibility
source_page: https://www.nuorder.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NuORDER\naid: nuorder\nurl: https://www.nuorder.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or fraudulent activity\n  text: NuORDER may suspend or terminate your access or use of the Services immediately and without notice, if you\n    use the Service to (i) engage in an illegal or fraudulent activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nuorder/eligibility/nuorder-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from NuORDER's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- B2B Commerce
- Wholesale
- E-Commerce
- Retail
- Fashion
- Order Management
- Marketplace
---
