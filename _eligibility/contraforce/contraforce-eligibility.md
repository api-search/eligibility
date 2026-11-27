---
api_specs:
- filename: contraforce-agent-tools-api-openapi.yml
  format: yaml
  label: Contraforce Agent Tools API
  slug: contraforce-agent-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-agent-tools-api-openapi.yml
- filename: contraforce-azure-resources-api-openapi.yml
  format: yaml
  label: Contraforce Azure resources API
  slug: contraforce-azure-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-azure-resources-api-openapi.yml
- filename: contraforce-cross-workspace-data-sources-api-openapi.yml
  format: yaml
  label: Contraforce Cross-workspace data sources API
  slug: contraforce-cross-workspace-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-cross-workspace-data-sources-api-openapi.yml
- filename: contraforce-cross-workspace-gamebooks-api-openapi.yml
  format: yaml
  label: Contraforce Cross-workspace gamebooks API
  slug: contraforce-cross-workspace-gamebooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-cross-workspace-gamebooks-api-openapi.yml
- filename: contraforce-cross-workspace-incidents-api-openapi.yml
  format: yaml
  label: Contraforce Cross-workspace incidents API
  slug: contraforce-cross-workspace-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-cross-workspace-incidents-api-openapi.yml
- filename: contraforce-data-sources-api-openapi.yml
  format: yaml
  label: Contraforce Data sources API
  slug: contraforce-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-data-sources-api-openapi.yml
- filename: contraforce-export-api-openapi.yml
  format: yaml
  label: Contraforce Export API
  slug: contraforce-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-export-api-openapi.yml
- filename: contraforce-gamebooks-api-openapi.yml
  format: yaml
  label: Contraforce Gamebooks API
  slug: contraforce-gamebooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-gamebooks-api-openapi.yml
- filename: contraforce-incidents-api-openapi.yml
  format: yaml
  label: Contraforce Incidents API
  slug: contraforce-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-incidents-api-openapi.yml
- filename: contraforce-investigation-api-openapi.yml
  format: yaml
  label: Contraforce Investigation API
  slug: contraforce-investigation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-investigation-api-openapi.yml
- filename: contraforce-service-accounts-api-openapi.yml
  format: yaml
  label: Contraforce Service accounts API
  slug: contraforce-service-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-service-accounts-api-openapi.yml
- filename: contraforce-service-tickets-api-openapi.yml
  format: yaml
  label: Contraforce Service tickets API
  slug: contraforce-service-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-service-tickets-api-openapi.yml
- filename: contraforce-users-api-openapi.yml
  format: yaml
  label: Contraforce Users API
  slug: contraforce-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-users-api-openapi.yml
- filename: contraforce-webhooks-api-openapi.yml
  format: yaml
  label: Contraforce Webhooks API
  slug: contraforce-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contraforce/openapi/contraforce-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are operated and hosted by ContraForce in the United States.
  minimum_age:
    text: confirm they’re 18 years or older.
    value: '18'
  restricted_uses:
  - summary: Illegal or unlawful use
    text: ContraForce prohibits using services for illegal purposes or violating any laws.
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
name: Contraforce
provenance_date: '2026-11-09'
provider_name: Contraforce
provider_slug: contraforce
slug: contraforce-eligibility
source_date: '2026-11-09'
source_filename: contraforce-eligibility.yml
source_heading: Eligibility
source_page: https://www.contraforce.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Contraforce\naid: contraforce\nurl: https://www.contraforce.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are operated and hosted by ContraForce in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unlawful use\n  text: ContraForce prohibits using services for illegal purposes or violating any laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: confirm they’re 18 years or older.\n"
source_yaml_url: https://artifacts.apis.io/contraforce/eligibility/contraforce-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Contraforce's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Software-as-a-Service
- Cybersecurity
- Microsoft
- MSP
---
