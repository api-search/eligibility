---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: We provide this Website for use only by persons located in the United Kingdom.
  entity_types:
  - text: If you use the Website on behalf of an entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorised representative of the entity
    type: business
  minimum_age:
    text: By using our Website, you represent that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use our site only for lawful purposes.
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
name: SAVA
provenance_date: '2026-11-10'
provider_name: SAVA
provider_slug: sava
slug: sava-eligibility
source_date: '2026-11-10'
source_filename: sava-eligibility.yml
source_heading: Eligibility
source_page: https://www.sava.health/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SAVA\naid: sava\nurl: https://www.sava.health/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: We provide this Website for use only by persons located in the United Kingdom.\nentity_types:\n- type: business\n  text: If you use the Website on behalf of an entity then “you” includes you and that entity, and you represent\n    and warrant that (a) you are an authorised representative of the entity\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use our site only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: By using our Website, you represent that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/sava/eligibility/sava-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SAVA's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Biosensor
- Wearables
- Continuous Monitoring
- Preventative Health
- Health Tech
- MCP
---
