---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: the Site and Services are not available to individuals or entities in countries that are subject to U.S. government sanctions or embargoes imposed by the Office of Foreign Assets Control (OFAC) or similar regulations.
  entity_types:
  - text: you must be able to form a legally binding contract with us
    type: individual
  - text: If the user is an organization, you affirm you have the right, power and authority to enter into this agreement on behalf of the organization and bind the organization to its terms.
    type: business
  minimum_age:
    text: you are at least the age of majority in Your jurisdiction
    value: age of majority
  restricted_uses:
  - summary: US persons excluded
    text: SUCH ACCESS AND FUNCTIONALITY IS NOT PERMITTED FOR USE BY ANY US PERSON.
  - summary: Weapons development
    text: You also agree not to use our Services for any purposes prohibited by United States law, including the development, design, manufacture, or production of missiles, or nuclear, chemical, or biological weapons.
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
name: Layer3
provenance_date: '2026-11-09'
provider_name: Layer3
provider_slug: layer3
slug: layer3-eligibility
source_date: '2026-11-09'
source_filename: layer3-eligibility.yml
source_heading: Eligibility
source_page: https://app.layer3.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Layer3\naid: layer3\nurl: https://app.layer3.xyz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: the Site and Services are not available to individuals or entities in countries that are subject to U.S.\n    government sanctions or embargoes imposed by the Office of Foreign Assets Control (OFAC) or similar regulations.\nentity_types:\n- type: individual\n  text: you must be able to form a legally binding contract with us\n- type: business\n  text: If the user is an organization, you affirm you have the right, power and authority to enter into this agreement\n\
  \    on behalf of the organization and bind the organization to its terms.\nrestricted_uses:\n- summary: US persons excluded\n  text: SUCH ACCESS AND FUNCTIONALITY IS NOT PERMITTED FOR USE BY ANY US PERSON.\n- summary: Weapons development\n  text: You also agree not to use our Services for any purposes prohibited by United States law, including the development,\n    design, manufacture, or production of missiles, or nuclear, chemical, or biological weapons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are at least the age of majority in Your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/layer3/eligibility/layer3-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Layer3's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Web3
- Blockchain
- DeFi
- Rewards
- Onboarding
- Wallets
- Quests
---
