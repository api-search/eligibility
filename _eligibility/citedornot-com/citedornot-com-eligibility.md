---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old and capable of forming a binding contract to use the Service.
    value: '16'
  restricted_uses:
  - summary: Tracking unauthorised brands
    text: Use the Service to track brands, keywords, or competitors you do not have the right to monitor.
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
name: CitedOrNot
provenance_date: '2026-11-09'
provider_name: CitedOrNot
provider_slug: citedornot-com
slug: citedornot-com-eligibility
source_date: '2026-11-09'
source_filename: citedornot-com-eligibility.yml
source_heading: Eligibility
source_page: https://citedornot.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CitedOrNot\naid: citedornot-com\nurl: https://citedornot.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Tracking unauthorised brands\n  text: Use the Service to track brands, keywords, or competitors you do not have the right to monitor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old and capable of forming a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/citedornot-com/eligibility/citedornot-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from CitedOrNot's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Brands
- Analytics
- Visibility
---
