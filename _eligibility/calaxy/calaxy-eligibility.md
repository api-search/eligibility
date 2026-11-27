---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - RU
    - SY
    served: []
    text: 'For the purposes of the Terms, "Restricted Territory" means of Cuba, Iran, North Korea, Russia, Syria, the following regions of Ukraine: Crimea, Donetsk and Luhansk, or any other country to which the United States embargoes goods or imposes similar sanctions.'
  entity_types:
  - text: the Platform is intended for people 16 years of age or older
    type: individual
  minimum_age:
    text: you are 16 years of age or older
    value: '16'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Calaxy will review and approve or reject your application to become a Creator in its sole discretion.
excluded_countries:
- CU
- IR
- KP
- RU
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Calaxy
provenance_date: '2026-11-09'
provider_name: Calaxy
provider_slug: calaxy
slug: calaxy-eligibility
source_date: '2026-11-09'
source_filename: calaxy-eligibility.yml
source_heading: Eligibility
source_page: https://calaxy.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calaxy\naid: calaxy\nurl: https://calaxy.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - RU\n  - SY\n  text: 'For the purposes of the Terms, \"Restricted Territory\" means of Cuba, Iran, North Korea, Russia, Syria,\n    the following regions of Ukraine: Crimea, Donetsk and Luhansk, or any other country to which the United States\n    embargoes goods or imposes similar sanctions.'\nentity_types:\n- type: individual\n  text: the Platform is intended for people 16 years of age or older\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: true\n  text: Calaxy will review and approve or reject your application to become a Creator in its sole discretion.\nminimum_age:\n  value: '16'\n  text: you are 16 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/calaxy/eligibility/calaxy-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Calaxy's own page on 2026-11-09.
synthetic: false
tags:
- Decentralized
- Social
- Platform
- Creator Economy
- Community
---
