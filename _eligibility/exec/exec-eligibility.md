---
api_specs:
- filename: exec-collections-api-openapi.yml
  format: yaml
  label: Exec Collections API
  slug: exec-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-collections-api-openapi.yml
- filename: exec-knowledge-hub-folders-api-openapi.yml
  format: yaml
  label: Exec Knowledge Hub - Folders API
  slug: exec-knowledge-hub-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-knowledge-hub-folders-api-openapi.yml
- filename: exec-knowledge-hub-pages-api-openapi.yml
  format: yaml
  label: Exec Knowledge Hub - Pages API
  slug: exec-knowledge-hub-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-knowledge-hub-pages-api-openapi.yml
- filename: exec-knowledge-hub-sources-api-openapi.yml
  format: yaml
  label: Exec Knowledge Hub - Sources API
  slug: exec-knowledge-hub-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-knowledge-hub-sources-api-openapi.yml
- filename: exec-scenario-studio-api-openapi.yml
  format: yaml
  label: Exec Scenario Studio API
  slug: exec-scenario-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-scenario-studio-api-openapi.yml
- filename: exec-scenarios-api-openapi.yml
  format: yaml
  label: Exec Scenarios API
  slug: exec-scenarios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-scenarios-api-openapi.yml
- filename: exec-sessions-api-openapi.yml
  format: yaml
  label: Exec Sessions API
  slug: exec-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-sessions-api-openapi.yml
- filename: exec-skills-api-openapi.yml
  format: yaml
  label: Exec Skills API
  slug: exec-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-skills-api-openapi.yml
- filename: exec-workspace-api-openapi.yml
  format: yaml
  label: Exec Workspace API
  slug: exec-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-workspace-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are made available to individuals and entities seeking the Services, directly or indirectly, including but not limited to companies, agencies or other parties.
    type: business
  minimum_age:
    text: The Services are not for use by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Commercial gain
    text: You agree that you shall not transmit or upload to or through the Services any harmful code, or use or misappropriate the Services for your own commercial gain.
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
name: Exec
provenance_date: '2026-11-09'
provider_name: Exec
provider_slug: exec
slug: exec-eligibility
source_date: '2026-11-09'
source_filename: exec-eligibility.yml
source_heading: Eligibility
source_page: https://www.exec.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Exec\naid: exec\nurl: https://www.exec.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are made available to individuals and entities seeking the Services, directly or indirectly,\n    including but not limited to companies, agencies or other parties.\nrestricted_uses:\n- summary: Commercial gain\n  text: You agree that you shall not transmit or upload to or through the Services any harmful code, or use or misappropriate\n    the Services for your own commercial gain.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Services are not for use by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/exec/eligibility/exec-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Exec's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales Enablement
- Training
- Roleplay
- Coaching
- Learning
- Knowledge Management
- LMS
---
