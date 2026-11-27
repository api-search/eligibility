---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This site contains services that are available in the United States of America and its territories. Waystar makes no representation that this site, its contents, or the services offered through it are applicable or appropriate for use or consumption outside of the United States of America or its territories.
  minimum_age:
    text: null
    value: null
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
name: Waystar
provenance_date: '2026-11-10'
provider_name: Waystar
provider_slug: waystar
slug: waystar-eligibility
source_date: '2026-11-10'
source_filename: waystar-eligibility.yml
source_heading: Eligibility
source_page: https://www.waystar.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Waystar\naid: waystar\nurl: https://www.waystar.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This site contains services that are available in the United States of America and its territories. Waystar\n    makes no representation that this site, its contents, or the services offered through it are applicable or appropriate\n    for use or consumption outside of the United States of America or its territories.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/waystar/eligibility/waystar-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Waystar's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Revenue Cycle Management
- Clearinghouse
- Healthcare Payments
- Medical Billing
- X12 EDI
- Eligibility
- Claims
- Health Insurance
---
