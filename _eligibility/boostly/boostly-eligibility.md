---
claim_count: 2
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
  - summary: No lending or leasing decisions
    text: (k) use the Service in connection with making any lending or leasing financial decision;
  - summary: No Prohibited Data
    text: Customer (including Users) will not provide to, or otherwise make available via, the Service any Prohibited Data
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
name: Boostly
provenance_date: '2026-11-09'
provider_name: Boostly
provider_slug: boostly
slug: boostly-eligibility
source_date: '2026-11-09'
source_filename: boostly-eligibility.yml
source_heading: Eligibility
source_page: https://www.boostly.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boostly\naid: boostly\nurl: https://www.boostly.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No lending or leasing decisions\n  text: (k) use the Service in connection with making any lending or leasing financial decision;\n- summary: No Prohibited Data\n  text: Customer (including Users) will not provide to, or otherwise make available via, the Service any Prohibited\n    Data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boostly/eligibility/boostly-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Boostly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SMS Marketing
- Restaurant
- Customer Engagement
- Analytics
---
