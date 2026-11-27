---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for users located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States. Access to the Service from countries or territories where such access is illegal is strictly prohibited.
  minimum_age:
    text: At the time you make any Purchase, you are at least the age of majority in your state or province of residence
    value: null
  restricted_uses:
  - summary: Access from countries where illegal
    text: Access to the Service from countries or territories where such access is illegal is strictly prohibited.
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
name: Better Place Forests
provenance_date: '2026-11-09'
provider_name: Better Place Forests
provider_slug: better-place-forests
slug: better-place-forests-eligibility
source_date: '2026-11-09'
source_filename: better-place-forests-eligibility.yml
source_heading: Eligibility
source_page: https://betterplaceforests.org/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Better Place Forests\naid: better-place-forests\nurl: https://betterplaceforests.org/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for users located within the United States. We make no representation that the Service\n    is appropriate or available for use outside of the United States. Access to the Service from countries or territories\n    where such access is illegal is strictly prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Access from countries where illegal\n  text: Access to the Service from countries or territories where\
  \ such access is illegal is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: At the time you make any Purchase, you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/better-place-forests/eligibility/better-place-forests-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Better Place Forests's own page on 2026-11-09.
synthetic: false
tags:
- Non-Profit
- Memorial
- Forest Conservation
- Grief Support
- Environmental
---
