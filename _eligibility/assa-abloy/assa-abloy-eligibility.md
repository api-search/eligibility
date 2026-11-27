---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: L’Acheteur est l’acheteur de biens et/ou de services d’ASSA ABLOY.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Assa Abloy
provenance_date: '2026-11-09'
provider_name: Assa Abloy
provider_slug: assa-abloy
slug: assa-abloy-eligibility
source_date: '2026-11-09'
source_filename: assa-abloy-eligibility.yml
source_heading: Eligibility
source_page: https://www.assaabloy.com/be/fr/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Assa Abloy\naid: assa-abloy\nurl: https://www.assaabloy.com/be/fr/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: L’Acheteur est l’acheteur de biens et/ou de services d’ASSA ABLOY.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/assa-abloy/eligibility/assa-abloy-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Assa Abloy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Access Control
- IoT
- Smart Buildings
---
