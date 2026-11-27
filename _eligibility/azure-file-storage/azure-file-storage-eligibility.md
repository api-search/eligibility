---
api_specs:
- filename: azure-file-storage-azure-file-storage-api-openapi.yml
  format: yaml
  label: Azure Files Azure File Storage API
  slug: azure-file-storage-azure-file-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azure-file-storage/openapi/azure-file-storage-azure-file-storage-api-openapi.yml
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
  - summary: 'AI services: no reverse engineering'
    text: You may not use the AI services to discover any underlying components of the models, algorithms, and systems.
  - summary: 'AI services: no training other AI services'
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
name: Azure Files
provenance_date: '2026-11-09'
provider_name: Azure Files
provider_slug: azure-file-storage
slug: azure-file-storage-eligibility
source_date: '2026-11-09'
source_filename: azure-file-storage-eligibility.yml
source_heading: Eligibility
source_page: https://www.microsoft.com/en-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azure Files\naid: azure-file-storage\nurl: https://www.microsoft.com/en-us/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Unless otherwise specified, the Services are for your personal and non-commercial use.\nrestricted_uses:\n- summary: 'AI services: no reverse engineering'\n  text: You may not use the AI services to discover any underlying components of the models, algorithms, and systems.\n- summary: 'AI services: no training other AI services'\n  text: You may not use the AI services, or data from the AI services,\
  \ to create, train, or improve (directly or\n    indirectly) any other AI service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/azure-file-storage/eligibility/azure-file-storage-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Azure Files's own page on 2026-11-09.
synthetic: false
tags:
- Storage
- File Storage
- File Shares
- NFS
- Cloud
- Microsoft Azure
- Server Message Block
---
