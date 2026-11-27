---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If acting on behalf of an entity, you have authority to bind such entity
    type: business
  minimum_age:
    text: You are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Export control and sanctions
    text: Use the Services in violation of export control or sanctions laws
  - summary: Unlawful surveillance
    text: Use the Services to conduct unlawful surveillance or violate privacy rights
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
name: Levo
provenance_date: '2026-11-09'
provider_name: Levo
provider_slug: levo
slug: levo-eligibility
source_date: '2026-11-09'
source_filename: levo-eligibility.yml
source_heading: Eligibility
source_page: https://www.levo.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Levo\naid: levo\nurl: https://www.levo.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If acting on behalf of an entity, you have authority to bind such entity\nrestricted_uses:\n- summary: Export control and sanctions\n  text: Use the Services in violation of export control or sanctions laws\n- summary: Unlawful surveillance\n  text: Use the Services to conduct unlawful surveillance or violate privacy rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/levo/eligibility/levo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Levo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Artificial Intelligence
- Platform
---
