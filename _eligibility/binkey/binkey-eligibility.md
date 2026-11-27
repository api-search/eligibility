---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may use the Services only if you are a resident of the United States or one of its territories
  entity_types:
  - text: You may use the Services only if you are a resident of the United States or one of its territories
    type: individual
  - text: If you open a Binkey Account on behalf of a company, organization, or other entity, then (i) “you” includes you and that entity
    type: business
  minimum_age:
    text: Any use or access to the Services by anyone under 18 is strictly prohibited and in violation of this Agreement.
    value: '18'
  restricted_uses:
  - summary: Restricted goods or services purchases
    text: You will not, without Binkey’s prior written consent, use the Service to purchase Restricted Goods or Services
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
name: Binkey
provenance_date: '2026-11-09'
provider_name: Binkey
provider_slug: binkey
slug: binkey-eligibility
source_date: '2026-11-09'
source_filename: binkey-eligibility.yml
source_heading: Eligibility
source_page: https://www.binkey.com/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Binkey\naid: binkey\nurl: https://www.binkey.com/terms-of-service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may use the Services only if you are a resident of the United States or one of its territories\nentity_types:\n- type: individual\n  text: You may use the Services only if you are a resident of the United States or one of its territories\n- type: business\n  text: If you open a Binkey Account on behalf of a company, organization, or other entity, then (i) “you” includes\n    you and that entity\nrestricted_uses:\n- summary: Restricted goods or services purchases\n\
  \  text: You will not, without Binkey’s prior written consent, use the Service to purchase Restricted Goods or Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the Services by anyone under 18 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/binkey/eligibility/binkey-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Binkey's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Payments
- Healthcare
- Loyalty
---
