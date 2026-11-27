---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that You are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a 'terrorist supporting' country, and that You are not listed on any U.S. Government list of prohibited or restricted parties (Apple device terms section).
  entity_types:
  - text: You hereby certify to Athos that You are at least 16 years of age.
    type: individual
  minimum_age:
    text: You hereby certify to Athos that You are at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Commercial use of Service
    text: rent, lease, or use the Service for any commercial purpose
  - summary: Unlawful use
    text: use the Service for any unlawful purpose
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
name: Athos
provenance_date: '2026-11-09'
provider_name: Athos
provider_slug: athos
slug: athos-eligibility
source_date: '2026-11-09'
source_filename: athos-eligibility.yml
source_heading: Eligibility
source_page: https://www.liveathos.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Athos\naid: athos\nurl: https://www.liveathos.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that You are not located in a country subject to a U.S. Government embargo, or\n    that has been designated by the U.S. Government as a 'terrorist supporting' country, and that You are not listed\n    on any U.S. Government list of prohibited or restricted parties (Apple device terms section).\nentity_types:\n- type: individual\n  text: You hereby certify to Athos that You are at least 16 years of age.\nrestricted_uses:\n- summary: Commercial\
  \ use of Service\n  text: rent, lease, or use the Service for any commercial purpose\n- summary: Unlawful use\n  text: use the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You hereby certify to Athos that You are at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/athos/eligibility/athos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Athos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wearables
- Fitness
- Sports Performance
- Electromyography
- Health
- Hardware
- IoT
---
