---
api_specs:
- filename: validic-devices-api-openapi.yml
  format: yaml
  label: Validic Devices API
  slug: validic-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-devices-api-openapi.yml
- filename: validic-marketplace-connections-api-openapi.yml
  format: yaml
  label: Validic Marketplace & Connections API
  slug: validic-marketplace-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-marketplace-connections-api-openapi.yml
- filename: validic-observations-data-api-openapi.yml
  format: yaml
  label: Validic Observations & Data API
  slug: validic-observations-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-observations-data-api-openapi.yml
- filename: validic-push-service-api-openapi.yml
  format: yaml
  label: Validic Push Service API
  slug: validic-push-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-push-service-api-openapi.yml
- filename: validic-streaming-api-openapi.yml
  format: yaml
  label: Validic Streaming API
  slug: validic-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-streaming-api-openapi.yml
- filename: validic-users-api-openapi.yml
  format: yaml
  label: Validic Users API
  slug: validic-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-users-api-openapi.yml
- filename: validic-measurements-api-openapi.yml
  format: yaml
  label: Validic Measurements API
  slug: validic-measurements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-measurements-api-openapi.yml
- filename: validic-organizations-api-openapi.yml
  format: yaml
  label: Validic Organizations API
  slug: validic-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-organizations-api-openapi.yml
- filename: validic-streams-api-openapi.yml
  format: yaml
  label: Validic Streams API
  slug: validic-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/validic/openapi/validic-streams-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Equipment for medical purposes only
    text: use the Equipment only for medical purposes and not for personal, family, or household purposes
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
name: Validic
provenance_date: '2026-11-10'
provider_name: Validic
provider_slug: validic
slug: validic-eligibility
source_date: '2026-11-10'
source_filename: validic-eligibility.yml
source_heading: Eligibility
source_page: https://validic.com/online-service-agreement-inform/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Validic\naid: validic\nurl: https://validic.com/online-service-agreement-inform/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Equipment for medical purposes only\n  text: use the Equipment only for medical purposes and not for personal, family, or household purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/validic/eligibility/validic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Validic's own page on 2026-11-10.
synthetic: false
tags:
- Health Data
- Digital Health
- Wearables
- Remote Patient Monitoring
- Health IoT
- Interoperability
- HIPAA
---
