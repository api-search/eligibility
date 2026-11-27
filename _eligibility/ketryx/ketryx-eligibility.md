---
api_specs:
- filename: ketryx-artifacts-api-openapi.yml
  format: yaml
  label: Ketryx Artifacts API
  slug: ketryx-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ketryx/openapi/ketryx-artifacts-api-openapi.yml
- filename: ketryx-builds-api-openapi.yml
  format: yaml
  label: Ketryx Builds API
  slug: ketryx-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ketryx/openapi/ketryx-builds-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal or sensitive data in Customer Software
    text: Customer will not deliver to Ketryx any Customer Software or data that contains personal information or other sensitive information.
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
name: Ketryx
provenance_date: '2026-11-09'
provider_name: Ketryx
provider_slug: ketryx
slug: ketryx-eligibility
source_date: '2026-11-09'
source_filename: ketryx-eligibility.yml
source_heading: Eligibility
source_page: https://www.ketryx.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ketryx\naid: ketryx\nurl: https://www.ketryx.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No personal or sensitive data in Customer Software\n  text: Customer will not deliver to Ketryx any Customer Software or data that contains personal information or\n    other sensitive information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ketryx/eligibility/ketryx-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Ketryx's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Medical Devices
- Life Sciences
- Compliance
- Regulatory
- Application Lifecycle Management
- Quality Management
- SBOM
- DevOps
- Healthcare
- Governance
- CI/CD
- Developer Tools
---
