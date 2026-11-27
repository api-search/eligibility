---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have the legal authority to enter into these terms.
    value: '18'
  restricted_uses:
  - summary: Malicious, illegal, or harmful content
    text: Use the Service to store or transmit malicious, illegal, or harmful content
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
name: Armbrain
provenance_date: '2026-11-09'
provider_name: Armbrain
provider_slug: armbrain-io
slug: armbrain-io-eligibility
source_date: '2026-11-09'
source_filename: armbrain-io-eligibility.yml
source_heading: Eligibility
source_page: https://armbrain.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Armbrain\naid: armbrain-io\nurl: https://armbrain.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization.\nrestricted_uses:\n- summary: Malicious, illegal, or harmful content\n  text: Use the Service to store or transmit malicious, illegal, or harmful content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and\
  \ have the legal authority to enter into these terms.\n"
source_yaml_url: https://artifacts.apis.io/armbrain-io/eligibility/armbrain-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Armbrain's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Productivity
- Software-as-a-Service
- Multi-Client
---
