---
api_specs:
- filename: lunar-configuration-api-openapi.yml
  format: yaml
  label: Lunar Configuration API
  slug: lunar-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar/openapi/lunar-configuration-api-openapi.yml
- filename: lunar-discovery-api-openapi.yml
  format: yaml
  label: Lunar Discovery API
  slug: lunar-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar/openapi/lunar-discovery-api-openapi.yml
- filename: lunar-doctor-api-openapi.yml
  format: yaml
  label: Lunar Doctor API
  slug: lunar-doctor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar/openapi/lunar-doctor-api-openapi.yml
- filename: lunar-flows-api-openapi.yml
  format: yaml
  label: Lunar Flows API
  slug: lunar-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar/openapi/lunar-flows-api-openapi.yml
- filename: lunar-handshake-api-openapi.yml
  format: yaml
  label: Lunar Handshake API
  slug: lunar-handshake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar/openapi/lunar-handshake-api-openapi.yml
- filename: lunar-policies-api-openapi.yml
  format: yaml
  label: Lunar Policies API
  slug: lunar-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar/openapi/lunar-policies-api-openapi.yml
- filename: lunar-health-api-openapi.yml
  format: yaml
  label: Lunar Health API
  slug: lunar-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar/openapi/lunar-health-api-openapi.yml
- filename: lunar-proxy-api-openapi.yml
  format: yaml
  label: Lunar Proxy API
  slug: lunar-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lunar/openapi/lunar-proxy-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of and access to the Services are void where prohibited by law.
  minimum_age:
    text: you are above the age of majority as determined by the applicable law in your jurisdiction of residency.
    value: age of majority
  restricted_uses:
  - summary: Private, non-commercial use
    text: use the Services (including any webpage or data that passes through our web domain), domain names, URLs, databases, functions or its content other than for private, non-commercial purposes (unless subject to our written permission and under a commercial contract between us regarding your commercial use).
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
name: Lunar
provenance_date: '2026-11-10'
provider_name: Lunar
provider_slug: lunar
slug: lunar-eligibility
source_date: '2026-11-10'
source_filename: lunar-eligibility.yml
source_heading: Eligibility
source_page: https://www.lunar.dev/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lunar\naid: lunar\nurl: https://www.lunar.dev/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of and access to the Services are void where prohibited by law.\nentity_types: []\nrestricted_uses:\n- summary: Private, non-commercial use\n  text: use the Services (including any webpage or data that passes through our web domain), domain names, URLs,\n    databases, functions or its content other than for private, non-commercial purposes (unless subject to our written\n    permission and under a commercial contract between us regarding your commercial use).\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are above the age of majority as determined by the applicable law in your jurisdiction of residency.\n"
source_yaml_url: https://artifacts.apis.io/lunar/eligibility/lunar-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Lunar's own page on 2026-11-10.
synthetic: false
tags:
- API Management
- API Gateway
- AI Gateway
- MCP Gateway
- Rate Limiting
- Quota Enforcement
- API Monetization
- Traffic Management
- API Governance
- Cost Controls
- Observability
---
