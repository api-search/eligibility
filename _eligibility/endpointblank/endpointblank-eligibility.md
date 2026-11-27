---
api_specs:
- filename: endpointblank-agent-oauth-api-openapi.yml
  format: yaml
  label: Bengal Technologies Agent Oauth API
  slug: endpointblank-agent-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-agent-oauth-api-openapi.yml
- filename: endpointblank-api-packages-api-openapi.yml
  format: yaml
  label: Bengal Technologies Api Packages API
  slug: endpointblank-api-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-api-packages-api-openapi.yml
- filename: endpointblank-applications-api-openapi.yml
  format: yaml
  label: Bengal Technologies Applications API
  slug: endpointblank-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-applications-api-openapi.yml
- filename: endpointblank-authorize-api-openapi.yml
  format: yaml
  label: Bengal Technologies Authorize API
  slug: endpointblank-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-authorize-api-openapi.yml
- filename: endpointblank-callback-api-openapi.yml
  format: yaml
  label: Bengal Technologies Callback API
  slug: endpointblank-callback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-callback-api-openapi.yml
- filename: endpointblank-clients-api-openapi.yml
  format: yaml
  label: Bengal Technologies Clients API
  slug: endpointblank-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-clients-api-openapi.yml
- filename: endpointblank-credentials-api-openapi.yml
  format: yaml
  label: Bengal Technologies Credentials API
  slug: endpointblank-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-credentials-api-openapi.yml
- filename: endpointblank-endpoints-api-openapi.yml
  format: yaml
  label: Bengal Technologies Endpoints API
  slug: endpointblank-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-endpoints-api-openapi.yml
- filename: endpointblank-environments-api-openapi.yml
  format: yaml
  label: Bengal Technologies Environments API
  slug: endpointblank-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-environments-api-openapi.yml
- filename: endpointblank-organization-api-openapi.yml
  format: yaml
  label: Bengal Technologies Organization API
  slug: endpointblank-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-organization-api-openapi.yml
- filename: endpointblank-well-known-api-openapi.yml
  format: yaml
  label: Bengal Technologies .well Known API
  slug: endpointblank-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endpointblank/openapi/endpointblank-well-known-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service, both this website and the application, is intended for use in the United States. We offer and market it to United States businesses only
  entity_types:
  - text: We offer and market it to United States businesses only
    type: business
  - text: You must be at least 18 years old and able to form a binding contract to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Sensitive data types
    text: do not send data you are not permitted to share or that the Service is not designed to protect (such as payment card or health data)
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
name: Bengal Technologies
provenance_date: '2026-11-09'
provider_name: Bengal Technologies
provider_slug: endpointblank
slug: endpointblank-eligibility
source_date: '2026-11-09'
source_filename: endpointblank-eligibility.yml
source_heading: Eligibility
source_page: https://endpointblank.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bengal Technologies\naid: endpointblank\nurl: https://endpointblank.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service, both this website and the application, is intended for use in the United States. We offer and\n    market it to United States businesses only\nentity_types:\n- type: business\n  text: We offer and market it to United States businesses only\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\nrestricted_uses:\n- summary: Sensitive data types\n  text: do not send data you are\
  \ not permitted to share or that the Service is not designed to protect (such as\n    payment card or health data)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/endpointblank/eligibility/endpointblank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bengal Technologies's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Management
- Versioning
- Authentication
- Monitoring
---
