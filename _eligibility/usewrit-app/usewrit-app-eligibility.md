---
api_specs:
- filename: usewrit-app-agent-api-openapi.yml
  format: yaml
  label: usewrit-app Agent API
  slug: usewrit-app-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-agent-api-openapi.yml
- filename: usewrit-app-automations-api-openapi.yml
  format: yaml
  label: usewrit-app Automations API
  slug: usewrit-app-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-automations-api-openapi.yml
- filename: usewrit-app-cloud-api-openapi.yml
  format: yaml
  label: usewrit-app Cloud API
  slug: usewrit-app-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-cloud-api-openapi.yml
- filename: usewrit-app-crawl-api-openapi.yml
  format: yaml
  label: usewrit-app Crawl API
  slug: usewrit-app-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-crawl-api-openapi.yml
- filename: usewrit-app-data-api-openapi.yml
  format: yaml
  label: usewrit-app Data API
  slug: usewrit-app-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-data-api-openapi.yml
- filename: usewrit-app-datasets-api-openapi.yml
  format: yaml
  label: usewrit-app Datasets API
  slug: usewrit-app-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-datasets-api-openapi.yml
- filename: usewrit-app-extractors-api-openapi.yml
  format: yaml
  label: usewrit-app Extractors API
  slug: usewrit-app-extractors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-extractors-api-openapi.yml
- filename: usewrit-app-files-api-openapi.yml
  format: yaml
  label: usewrit-app Files API
  slug: usewrit-app-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-files-api-openapi.yml
- filename: usewrit-app-keys-api-openapi.yml
  format: yaml
  label: usewrit-app Keys API
  slug: usewrit-app-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-keys-api-openapi.yml
- filename: usewrit-app-monitors-api-openapi.yml
  format: yaml
  label: usewrit-app Monitors API
  slug: usewrit-app-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-monitors-api-openapi.yml
- filename: usewrit-app-personas-api-openapi.yml
  format: yaml
  label: usewrit-app Personas API
  slug: usewrit-app-personas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-personas-api-openapi.yml
- filename: usewrit-app-runs-api-openapi.yml
  format: yaml
  label: usewrit-app Runs API
  slug: usewrit-app-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-runs-api-openapi.yml
- filename: usewrit-app-secrets-api-openapi.yml
  format: yaml
  label: usewrit-app Secrets API
  slug: usewrit-app-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-secrets-api-openapi.yml
- filename: usewrit-app-selectors-api-openapi.yml
  format: yaml
  label: usewrit-app Selectors API
  slug: usewrit-app-selectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-selectors-api-openapi.yml
- filename: usewrit-app-vault-api-openapi.yml
  format: yaml
  label: usewrit-app Vault API
  slug: usewrit-app-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-vault-api-openapi.yml
- filename: usewrit-app-workflows-api-openapi.yml
  format: yaml
  label: usewrit-app Workflows API
  slug: usewrit-app-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-workflows-api-openapi.yml
- filename: usewrit-app-ws-ticket-api-openapi.yml
  format: yaml
  label: usewrit-app Ws Ticket API
  slug: usewrit-app-ws-ticket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usewrit-app/openapi/usewrit-app-ws-ticket-api-openapi.yml
claim_count: 2
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
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate information and a verified email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: usewrit-app
provenance_date: '2026-11-10'
provider_name: usewrit-app
provider_slug: usewrit-app
slug: usewrit-app-eligibility
source_date: '2026-11-10'
source_filename: usewrit-app-eligibility.yml
source_heading: Eligibility
source_page: https://usewrit.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: usewrit-app\naid: usewrit-app\nurl: https://usewrit.app/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate information and a verified email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/usewrit-app/eligibility/usewrit-app-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from usewrit-app's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- MCP
- No-Code
- Software-as-a-Service
---
