---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Services, you represent that you are at least 18 years of age and are legally authorized to enter into these Terms.
    type: individual
  - text: If you use the Services on behalf of an entity, then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: By using the Services, you represent that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Investigational device information
    text: THE SERVICES PROVIDE INFORMATION CONCERNING AN INVESTIGATIONAL DEVICE, WHICH IS LIMITED BY FEDERAL (U.S.) LAW TO INVESTIGATIONAL USE.
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
name: Synchron
provenance_date: '2026-11-10'
provider_name: Synchron
provider_slug: synchron
slug: synchron-eligibility
source_date: '2026-11-10'
source_filename: synchron-eligibility.yml
source_heading: Eligibility
source_page: https://synchron.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Synchron\naid: synchron\nurl: https://synchron.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Services, you represent that you are at least 18 years of age and are legally authorized to\n    enter into these Terms.\n- type: business\n  text: If you use the Services on behalf of an entity, then “you” includes you and that entity, and you represent\n    and warrant that (a) you are an authorized representative of the entity\nrestricted_uses:\n- summary: Investigational device information\n  text: THE SERVICES\
  \ PROVIDE INFORMATION CONCERNING AN INVESTIGATIONAL DEVICE, WHICH IS LIMITED BY FEDERAL (U.S.)\n    LAW TO INVESTIGATIONAL USE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Services, you represent that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/synchron/eligibility/synchron-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Synchron's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Brain-Computer Interface
- Neurotechnology
- Medical Devices
- Implantable Devices
- Health
- Neurology
- Assistive Technology
---
