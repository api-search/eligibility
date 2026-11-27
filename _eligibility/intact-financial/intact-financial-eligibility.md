---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: Only Canadian residents who can validly be bound by an agreement under applicable laws can use this Site.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use or use in prohibited areas
    text: Individuals residing in an area where the access to or use of the Site or any part of is illegal or prohibited are not permitted to use the Site.
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
name: Intact Financial
provenance_date: '2026-11-09'
provider_name: Intact Financial
provider_slug: intact-financial
slug: intact-financial-eligibility
source_date: '2026-11-09'
source_filename: intact-financial-eligibility.yml
source_heading: Eligibility
source_page: https://www.intactfc.com/terms-and-conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Intact Financial\naid: intact-financial\nurl: https://www.intactfc.com/terms-and-conditions-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: Only Canadian residents who can validly be bound by an agreement under applicable laws can use this Site.\nentity_types: []\nrestricted_uses:\n- summary: Illegal use or use in prohibited areas\n  text: Individuals residing in an area where the access to or use of the Site or any part of is illegal or prohibited\n    are not permitted to use the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/intact-financial/eligibility/intact-financial-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Intact Financial's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Canada
- Property and Casualty
- Carrier
- Underwriting
- Claims
- CSIO
---
