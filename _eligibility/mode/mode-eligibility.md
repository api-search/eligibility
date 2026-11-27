---
api_specs:
- filename: mode-account-api-openapi.yml
  format: yaml
  label: Mode Account API
  slug: mode-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-account-api-openapi.yml
- filename: mode-audit-logs-api-openapi.yml
  format: yaml
  label: Mode Audit Logs API
  slug: mode-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-audit-logs-api-openapi.yml
- filename: mode-data-sources-api-openapi.yml
  format: yaml
  label: Mode Data Sources API
  slug: mode-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-data-sources-api-openapi.yml
- filename: mode-datasets-api-openapi.yml
  format: yaml
  label: Mode Datasets API
  slug: mode-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-datasets-api-openapi.yml
- filename: mode-definitions-api-openapi.yml
  format: yaml
  label: Mode Definitions API
  slug: mode-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-definitions-api-openapi.yml
- filename: mode-groups-api-openapi.yml
  format: yaml
  label: Mode Groups API
  slug: mode-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-groups-api-openapi.yml
- filename: mode-invites-api-openapi.yml
  format: yaml
  label: Mode Invites API
  slug: mode-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-invites-api-openapi.yml
- filename: mode-memberships-api-openapi.yml
  format: yaml
  label: Mode Memberships API
  slug: mode-memberships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-memberships-api-openapi.yml
- filename: mode-reports-api-openapi.yml
  format: yaml
  label: Mode Reports API
  slug: mode-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-reports-api-openapi.yml
- filename: mode-spaces-api-openapi.yml
  format: yaml
  label: Mode Spaces API
  slug: mode-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-spaces-api-openapi.yml
- filename: mode-verify-api-openapi.yml
  format: yaml
  label: Mode Verify API
  slug: mode-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mode/openapi/mode-verify-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended solely for individuals who are at least 13 years of age or older.
    type: individual
  - text: If you are a government user or otherwise accessing or using the Service in your capacity as an employee of a government or public entity, the Amendment to these Terms ( available here ) shall apply to you.
    type: government
  minimum_age:
    text: The Service is intended solely for individuals who are at least 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: Free tier user limits
    text: As a free Service, Mode Studio is subject to certain use limitations, including a limit on users per organization, and users may not avoid this limit by sharing their account information or passwords
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
name: Mode
provenance_date: '2026-11-10'
provider_name: Mode
provider_slug: mode
slug: mode-eligibility
source_date: '2026-11-10'
source_filename: mode-eligibility.yml
source_heading: Eligibility
source_page: https://www.thoughtspot.com/legal/mode/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mode\naid: mode\nurl: https://www.thoughtspot.com/legal/mode/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is intended solely for individuals who are at least 13 years of age or older.\n- type: government\n  text: If you are a government user or otherwise accessing or using the Service in your capacity as an employee\n    of a government or public entity, the Amendment to these Terms ( available here ) shall apply to you.\nrestricted_uses:\n- summary: Free tier user limits\n  text: As a free Service, Mode Studio is\
  \ subject to certain use limitations, including a limit on users per organization,\n    and users may not avoid this limit by sharing their account information or passwords\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is intended solely for individuals who are at least 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/mode/eligibility/mode-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mode's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Business Intelligence
- Analytics
- Data
- Reporting
- Dashboards
- SQL
- Data Stack
---
