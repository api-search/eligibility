---
api_specs:
- filename: nexthink-campaigns-api-openapi.yml
  format: yaml
  label: Nexthink Campaigns API
  slug: nexthink-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexthink/openapi/nexthink-campaigns-api-openapi.yml
- filename: nexthink-device-deletions-api-openapi.yml
  format: yaml
  label: Nexthink Device Deletions API
  slug: nexthink-device-deletions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexthink/openapi/nexthink-device-deletions-api-openapi.yml
- filename: nexthink-enrichment-api-openapi.yml
  format: yaml
  label: Nexthink Enrichment API
  slug: nexthink-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexthink/openapi/nexthink-enrichment-api-openapi.yml
- filename: nexthink-execute-api-openapi.yml
  format: yaml
  label: Nexthink Execute API
  slug: nexthink-execute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexthink/openapi/nexthink-execute-api-openapi.yml
- filename: nexthink-export-api-openapi.yml
  format: yaml
  label: Nexthink Export API
  slug: nexthink-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexthink/openapi/nexthink-export-api-openapi.yml
- filename: nexthink-handoff-api-api-openapi.yml
  format: yaml
  label: Nexthink Handoff API
  slug: nexthink-handoff-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexthink/openapi/nexthink-handoff-api-api-openapi.yml
- filename: nexthink-remote-actions-api-openapi.yml
  format: yaml
  label: Nexthink Remote actions API
  slug: nexthink-remote-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexthink/openapi/nexthink-remote-actions-api-openapi.yml
- filename: nexthink-workflows-api-openapi.yml
  format: yaml
  label: Nexthink Workflows API
  slug: nexthink-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nexthink/openapi/nexthink-workflows-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Please, select the terms specific to your physical address: Main Services Agreement (United States) Main Services Agreement (D-A-CH region) Main Services Agreement (France) Contrat-cadre de Services (France) Main Services Agreement (rest of the world)'
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
name: Nexthink
provenance_date: '2026-11-10'
provider_name: Nexthink
provider_slug: nexthink
slug: nexthink-eligibility
source_date: '2026-11-10'
source_filename: nexthink-eligibility.yml
source_heading: Eligibility
source_page: https://docs.nexthink.com/legal/services-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nexthink\naid: nexthink\nurl: https://docs.nexthink.com/legal/services-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Please, select the terms specific to your physical address: Main Services Agreement (United States) Main\n    Services Agreement (D-A-CH region) Main Services Agreement (France) Contrat-cadre de Services (France) Main\n    Services Agreement (rest of the world)'\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nexthink/eligibility/nexthink-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Nexthink's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Applications
- Digital Employee Experience
- Endpoint Analytics
- IT Operations
- Automation
- Observability
---
