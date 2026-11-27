---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in, or ordinarily resident in, a country or region under comprehensive US sanctions
  entity_types:
  - text: You must be at least 18 years old (or the age of majority where you live, if higher) to create an account, buy anything, create an API key or join the Creator or Affiliate programs.
    type: individual
  - text: If you accept for a company or other organization, it is bound, and you confirm you have authority to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority where you live, if higher)
    value: '18'
  restricted_uses:
  - summary: Sanctioned end uses
    text: for prohibited end uses (for example weapons of mass destruction or military end uses in restricted countries)
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
name: AnimatedWebs
provenance_date: '2026-11-09'
provider_name: AnimatedWebs
provider_slug: animatedwebs-com
slug: animatedwebs-com-eligibility
source_date: '2026-11-09'
source_filename: animatedwebs-com-eligibility.yml
source_heading: Eligibility
source_page: https://animatedwebs.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnimatedWebs\naid: animatedwebs-com\nurl: https://animatedwebs.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in, or ordinarily resident in, a country or region under\n    comprehensive US sanctions\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority where you live, if higher) to create an account,\n    buy anything, create an API key or join the Creator or Affiliate programs.\n- type: business\n  text: If you accept for a company or other organization, it is bound, and you\
  \ confirm you have authority to bind\n    it.\nrestricted_uses:\n- summary: Sanctioned end uses\n  text: for prohibited end uses (for example weapons of mass destruction or military end uses in restricted countries)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority where you live, if higher)\n"
source_yaml_url: https://artifacts.apis.io/animatedwebs-com/eligibility/animatedwebs-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AnimatedWebs's own page on 2026-11-09.
synthetic: false
tags:
- AnimatedWebs
- WebTemplates
- Animation
- Artificial Intelligence
- ThreeJS
- Motion Graphics
---
