---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Outschool Platform may only be used by individuals who have created a User account with the right and authority to enter into these Terms who are legal age to form a binding contract
    type: individual
  minimum_age:
    text: legal age to form a binding contract to register for the Service (in many jurisdictions, this age is 18)
    value: '18'
  restricted_uses:
  - summary: Illegal or prohibited content and conduct
    text: violate any applicable local, state, national or international law, or any regulations having the force of law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Outschool reserves the right to determine your eligibility for a trial, promotion or discount
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Outschool
provenance_date: '2026-11-10'
provider_name: Outschool
provider_slug: outschool
slug: outschool-eligibility
source_date: '2026-11-10'
source_filename: outschool-eligibility.yml
source_heading: Eligibility
source_page: https://outschool.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Outschool\naid: outschool\nurl: https://outschool.com/pages/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Outschool Platform may only be used by individuals who have created a User account with the right and\n    authority to enter into these Terms who are legal age to form a binding contract\nrestricted_uses:\n- summary: Illegal or prohibited content and conduct\n  text: violate any applicable local, state, national or international law, or any regulations having the force\n    of law\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: Outschool reserves the right to determine your eligibility for a trial, promotion or discount\nminimum_age:\n  value: '18'\n  text: legal age to form a binding contract to register for the Service (in many jurisdictions, this age is 18)\n"
source_yaml_url: https://artifacts.apis.io/outschool/eligibility/outschool-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Outschool's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EdTech
- E-Learning
- Education
- Marketplace
- Kids
- K-12
- Homeschool
---
