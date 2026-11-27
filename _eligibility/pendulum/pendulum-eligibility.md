---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use our Services.
  entity_types:
  - text: You must be 18 years of age or older and reside in the United States or any of its territories to use our Services.
    type: individual
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity with the authority to bind the entity to these Terms
    type: business
  minimum_age:
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use our Services.
    value: '18'
  restricted_uses:
  - summary: Medical advice substitution
    text: INFORMATION ON THE SITES IS NOT PROVIDED AS, NOR SHOULD IT SUBSTITUTE FOR MEDICAL ADVICE.
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
name: Pendulum
provenance_date: '2026-11-10'
provider_name: Pendulum
provider_slug: pendulum
slug: pendulum-eligibility
source_date: '2026-11-10'
source_filename: pendulum-eligibility.yml
source_heading: Eligibility
source_page: https://pendulumlife.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pendulum\naid: pendulum\nurl: https://pendulumlife.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use our\n    Services.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use our\n    Services.\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n    and you represent and warrant\
  \ that (a) you are an authorized representative of the entity with the authority\n    to bind the entity to these Terms\nrestricted_uses:\n- summary: Medical advice substitution\n  text: INFORMATION ON THE SITES IS NOT PROVIDED AS, NOR SHOULD IT SUBSTITUTE FOR MEDICAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use our\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/pendulum/eligibility/pendulum-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pendulum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Microbiome
- Probiotics
- Metabolic Health
- Consumer Health
- Supplements
- Direct to Consumer
---
