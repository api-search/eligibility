---
api_specs:
- filename: ambitioninc-account-api-openapi.yml
  format: yaml
  label: Ambitioninc Account API
  slug: ambitioninc-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ambitioninc/openapi/ambitioninc-account-api-openapi.yml
- filename: ambitioninc-data-api-openapi.yml
  format: yaml
  label: Ambitioninc Data API
  slug: ambitioninc-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ambitioninc/openapi/ambitioninc-data-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any use modification, reproduction, release, performance, display, or disclosure of such commercial software or commercial software documentation by the U.S. Government will be governed solely by the terms of this Agreement
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations
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
name: Ambitioninc
provenance_date: '2026-11-09'
provider_name: Ambitioninc
provider_slug: ambitioninc
slug: ambitioninc-eligibility
source_date: '2026-11-09'
source_filename: ambitioninc-eligibility.yml
source_heading: Eligibility
source_page: https://ambition.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ambitioninc\naid: ambitioninc\nurl: https://ambition.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: any use modification, reproduction, release, performance, display, or disclosure of such commercial software\n    or commercial software documentation by the U.S. Government will be governed solely by the terms of this Agreement\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services,\n    Software or anything related\
  \ thereto, or any direct product thereof in violation of any restrictions, laws or\n    regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ambitioninc/eligibility/ambitioninc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Ambitioninc's own page on 2026-11-09.
synthetic: false
tags:
- Software-as-a-Service
- Revenue Operations
- Sales Enablement
- Artificial Intelligence
- Platform
---
