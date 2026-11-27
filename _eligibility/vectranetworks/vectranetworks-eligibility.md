---
api_specs:
- filename: vectranetworks-accounts-api-openapi.yml
  format: yaml
  label: Vectra AI Accounts API
  slug: vectranetworks-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-accounts-api-openapi.yml
- filename: vectranetworks-assignment-outcomes-api-openapi.yml
  format: yaml
  label: Vectra AI Assignment Outcomes API
  slug: vectranetworks-assignment-outcomes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-assignment-outcomes-api-openapi.yml
- filename: vectranetworks-assignments-api-openapi.yml
  format: yaml
  label: Vectra AI Assignments API
  slug: vectranetworks-assignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-assignments-api-openapi.yml
- filename: vectranetworks-detections-api-openapi.yml
  format: yaml
  label: Vectra AI Detections API
  slug: vectranetworks-detections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-detections-api-openapi.yml
- filename: vectranetworks-entities-api-openapi.yml
  format: yaml
  label: Vectra AI Entities API
  slug: vectranetworks-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-entities-api-openapi.yml
- filename: vectranetworks-events-api-openapi.yml
  format: yaml
  label: Vectra AI Events API
  slug: vectranetworks-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-events-api-openapi.yml
- filename: vectranetworks-groups-api-openapi.yml
  format: yaml
  label: Vectra AI Groups API
  slug: vectranetworks-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-groups-api-openapi.yml
- filename: vectranetworks-health-api-openapi.yml
  format: yaml
  label: Vectra AI Health API
  slug: vectranetworks-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-health-api-openapi.yml
- filename: vectranetworks-hosts-api-openapi.yml
  format: yaml
  label: Vectra AI Hosts API
  slug: vectranetworks-hosts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-hosts-api-openapi.yml
- filename: vectranetworks-lockdown-api-openapi.yml
  format: yaml
  label: Vectra AI Lockdown API
  slug: vectranetworks-lockdown-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-lockdown-api-openapi.yml
- filename: vectranetworks-match-api-openapi.yml
  format: yaml
  label: Vectra AI Match API
  slug: vectranetworks-match-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-match-api-openapi.yml
- filename: vectranetworks-notes-api-openapi.yml
  format: yaml
  label: Vectra AI Notes API
  slug: vectranetworks-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-notes-api-openapi.yml
- filename: vectranetworks-proxies-api-openapi.yml
  format: yaml
  label: Vectra AI Proxies API
  slug: vectranetworks-proxies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-proxies-api-openapi.yml
- filename: vectranetworks-search-api-openapi.yml
  format: yaml
  label: Vectra AI Search API
  slug: vectranetworks-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-search-api-openapi.yml
- filename: vectranetworks-tagging-api-openapi.yml
  format: yaml
  label: Vectra AI Tagging API
  slug: vectranetworks-tagging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-tagging-api-openapi.yml
- filename: vectranetworks-threat-feeds-api-openapi.yml
  format: yaml
  label: Vectra AI Threat Feeds API
  slug: vectranetworks-threat-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-threat-feeds-api-openapi.yml
- filename: vectranetworks-users-api-openapi.yml
  format: yaml
  label: Vectra AI Users API
  slug: vectranetworks-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vectranetworks/openapi/vectranetworks-users-api-openapi.yml
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
  - summary: Export restrictions
    text: Products may not be exported without prior written consent of VECTRA.
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
name: Vectra AI
provenance_date: '2026-11-10'
provider_name: Vectra AI
provider_slug: vectranetworks
slug: vectranetworks-eligibility
source_date: '2026-11-10'
source_filename: vectranetworks-eligibility.yml
source_heading: Eligibility
source_page: https://www.vectra.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vectra AI\naid: vectranetworks\nurl: https://www.vectra.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: Products may not be exported without prior written consent of VECTRA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vectranetworks/eligibility/vectranetworks-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Vectra AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Network Detection and Response
- Threat Detection
- Security Operations
- Artificial Intelligence
- SIEM
---
