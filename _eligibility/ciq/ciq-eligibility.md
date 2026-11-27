---
api_specs:
- filename: ciq-openapi-generated.yml
  format: yaml
  label: CIQ API
  slug: ciq-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciq/openapi/_ae-authored/ciq-openapi-generated.yml
- filename: ciq-agent-api-openapi.yml
  format: yaml
  label: CIQ Agent API
  slug: ciq-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciq/openapi/ciq-agent-api-openapi.yml
- filename: ciq-ciq-api-api-openapi.yml
  format: yaml
  label: CIQ CIQ API
  slug: ciq-ciq-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciq/openapi/ciq-ciq-api-api-openapi.yml
- filename: ciq-data-api-openapi.yml
  format: yaml
  label: CIQ Data API
  slug: ciq-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciq/openapi/ciq-data-api-openapi.yml
- filename: ciq-dlv2-api-openapi.yml
  format: yaml
  label: CIQ Dlv2 API
  slug: ciq-dlv2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciq/openapi/ciq-dlv2-api-openapi.yml
- filename: ciq-models-api-openapi.yml
  format: yaml
  label: CIQ Models API
  slug: ciq-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciq/openapi/ciq-models-api-openapi.yml
- filename: ciq-path-api-openapi.yml
  format: yaml
  label: CIQ Path API
  slug: ciq-path-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciq/openapi/ciq-path-api-openapi.yml
- filename: ciq-sources-api-openapi.yml
  format: yaml
  label: CIQ Sources API
  slug: ciq-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciq/openapi/ciq-sources-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: User (or You) Indicates any natural person or legal entity using this Website.
    type: individual
  - text: User (or You) Indicates any natural person or legal entity using this Website.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No reselling of website or Service
    text: Users may not reproduce, duplicate, copy, sell, resell or exploit any portion of this Website and of its Service without the Owner’s express prior written permission
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
name: CIQ
provenance_date: '2026-11-09'
provider_name: CIQ
provider_slug: ciq
slug: ciq-eligibility
source_date: '2026-11-09'
source_filename: ciq-eligibility.yml
source_heading: Eligibility
source_page: https://ciq.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CIQ\naid: ciq\nurl: https://ciq.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: User (or You) Indicates any natural person or legal entity using this Website.\n- type: business\n  text: User (or You) Indicates any natural person or legal entity using this Website.\nrestricted_uses:\n- summary: No reselling of website or Service\n  text: Users may not reproduce, duplicate, copy, sell, resell or exploit any portion of this Website and of its\n    Service without the Owner’s express prior written permission\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ciq/eligibility/ciq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from CIQ's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Infrastructure
- Open Source
- Enterprise
- Cloud
---
