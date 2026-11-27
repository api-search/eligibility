---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be eighteen (18) years of age or older and reside in the United States or any of its territories to use the Services.
  entity_types:
  - text: You must be eighteen (18) years of age or older and reside in the United States or any of its territories to use the Services.
    type: individual
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: You must be eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: We hereby permit you to use the Services for your personal, non-commercial use only
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
name: Granted
provenance_date: '2026-11-09'
provider_name: Granted
provider_slug: granted
slug: granted-eligibility
source_date: '2026-11-09'
source_filename: granted-eligibility.yml
source_heading: Eligibility
source_page: https://grantedhealth.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Granted\naid: granted\nurl: https://grantedhealth.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be eighteen (18) years of age or older and reside in the United States or any of its territories\n    to use the Services.\nentity_types:\n- type: individual\n  text: You must be eighteen (18) years of age or older and reside in the United States or any of its territories\n    to use the Services.\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n    and you represent and warrant\
  \ that (a) you are an authorized representative of the entity\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: We hereby permit you to use the Services for your personal, non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/granted/eligibility/granted-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Granted's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Medical Billing
- Health Insurance
- Consumer
- Artificial Intelligence
---
