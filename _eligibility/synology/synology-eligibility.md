---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are deemed to be a minor in Your country of residence and are not signing this Agreement on behalf of an entity, You shall obtain Your parent's or legal guardian's consent to legally use the Services.
    type: individual
  - text: You, or when you act on behalf of any entity, such entity ("You").
    type: business
  minimum_age:
    text: If You are deemed to be a minor in Your country of residence and are not signing this Agreement on behalf of an entity, You shall obtain Your parent's or legal guardian's consent to legally use the Services.
    value: null
  restricted_uses:
  - summary: Store unlawful data
    text: refrain from using the Services to store any data that do not comply with applicable laws, rules, and regulations, or that infringe on the rights of any third party.
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
name: Synology C2
provenance_date: '2026-11-10'
provider_name: Synology C2
provider_slug: synology
slug: synology-eligibility
source_date: '2026-11-10'
source_filename: synology-eligibility.yml
source_heading: Eligibility
source_page: https://c2.synology.com/en-global/legal/terms_conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Synology C2\naid: synology\nurl: https://c2.synology.com/en-global/legal/terms_conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If You are deemed to be a minor in Your country of residence and are not signing this Agreement on behalf\n    of an entity, You shall obtain Your parent's or legal guardian's consent to legally use the Services.\n- type: business\n  text: You, or when you act on behalf of any entity, such entity (\"You\").\nrestricted_uses:\n- summary: Store unlawful data\n  text: refrain from using the Services\
  \ to store any data that do not comply with applicable laws, rules, and regulations,\n    or that infringe on the rights of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: If You are deemed to be a minor in Your country of residence and are not signing this Agreement on behalf\n    of an entity, You shall obtain Your parent's or legal guardian's consent to legally use the Services.\n"
source_yaml_url: https://artifacts.apis.io/synology/eligibility/synology-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Synology C2's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud
- Backup
- Storage
- Enterprise
---
