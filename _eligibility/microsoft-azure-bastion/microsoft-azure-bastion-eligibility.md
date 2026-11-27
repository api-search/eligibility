---
api_specs:
- filename: microsoft-azure-bastion-bastionhosts-api-openapi.yml
  format: yaml
  label: Azure Bastion Bastion Hosts API
  slug: microsoft-azure-bastion-bastionhosts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-azure-bastion/openapi/microsoft-azure-bastion-bastionhosts-api-openapi.yml
- filename: microsoft-azure-bastion-bastionshareablelink-api-openapi.yml
  format: yaml
  label: Azure Bastion Bastion Shareable Link API
  slug: microsoft-azure-bastion-bastionshareablelink-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-azure-bastion/openapi/microsoft-azure-bastion-bastionshareablelink-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Unless otherwise specified, the Services are for your personal and non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AI services reverse engineering
    text: You may not use the AI services to discover any underlying components of the models, algorithms, and systems.
  - summary: No using AI service outputs to build AI
    text: You may not use the AI services, or data from the AI services, to create, train, or improve (directly or indirectly) any other AI service.
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
name: Azure Bastion
provenance_date: '2026-11-10'
provider_name: Azure Bastion
provider_slug: microsoft-azure-bastion
slug: microsoft-azure-bastion-eligibility
source_date: '2026-11-10'
source_filename: microsoft-azure-bastion-eligibility.yml
source_heading: Eligibility
source_page: https://www.microsoft.com/en-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azure Bastion\naid: microsoft-azure-bastion\nurl: https://www.microsoft.com/en-us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Unless otherwise specified, the Services are for your personal and non-commercial use.\nrestricted_uses:\n- summary: AI services reverse engineering\n  text: You may not use the AI services to discover any underlying components of the models, algorithms, and systems.\n- summary: No using AI service outputs to build AI\n  text: You may not use the AI services, or data from the AI services,\
  \ to create, train, or improve (directly or\n    indirectly) any other AI service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/microsoft-azure-bastion/eligibility/microsoft-azure-bastion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Azure Bastion's own page on 2026-11-10.
synthetic: false
tags:
- Bastion
- RDP
- Remote Access
- Secure Access
- SSH
---
