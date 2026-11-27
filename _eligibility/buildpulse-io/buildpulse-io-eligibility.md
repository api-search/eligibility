---
api_specs:
- filename: buildpulse-io-auth-api-openapi.yml
  format: yaml
  label: BuildPulse Auth API
  slug: buildpulse-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildpulse-io/openapi/buildpulse-io-auth-api-openapi.yml
- filename: buildpulse-io-badges-api-openapi.yml
  format: yaml
  label: BuildPulse Badges API
  slug: buildpulse-io-badges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildpulse-io/openapi/buildpulse-io-badges-api-openapi.yml
- filename: buildpulse-io-flaky-api-openapi.yml
  format: yaml
  label: BuildPulse Flaky API
  slug: buildpulse-io-flaky-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildpulse-io/openapi/buildpulse-io-flaky-api-openapi.yml
- filename: buildpulse-io-health-api-openapi.yml
  format: yaml
  label: BuildPulse Health API
  slug: buildpulse-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildpulse-io/openapi/buildpulse-io-health-api-openapi.yml
- filename: buildpulse-io-submissions-api-openapi.yml
  format: yaml
  label: BuildPulse Submissions API
  slug: buildpulse-io-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildpulse-io/openapi/buildpulse-io-submissions-api-openapi.yml
- filename: buildpulse-io-tests-api-openapi.yml
  format: yaml
  label: BuildPulse Tests API
  slug: buildpulse-io-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildpulse-io/openapi/buildpulse-io-tests-api-openapi.yml
- filename: buildpulse-io-webhooks-api-openapi.yml
  format: yaml
  label: BuildPulse Webhooks API
  slug: buildpulse-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildpulse-io/openapi/buildpulse-io-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not export, re-export, or otherwise access the Services in violation of Applicable Law, including in any embargoed country or jurisdiction.
  entity_types:
  - text: the individual or entity accessing or using the Services (“Customer,” “you,” or “your”)
    type: individual
  - text: If you are entering into this Agreement on behalf of a company, organization, or other entity, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Each party will comply with the export laws and regulations of the United States, the European Union, and other applicable jurisdictions.
  - summary: Sensitive data
    text: Customer will not use the Services to transmit to BuildPulse any financial or medical information, or any sensitive personal data
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
name: BuildPulse
provenance_date: '2026-11-09'
provider_name: BuildPulse
provider_slug: buildpulse-io
slug: buildpulse-io-eligibility
source_date: '2026-11-09'
source_filename: buildpulse-io-eligibility.yml
source_heading: Eligibility
source_page: https://buildpulse.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuildPulse\naid: buildpulse-io\nurl: https://buildpulse.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not export, re-export, or otherwise access the Services in violation of Applicable Law, including\n    in any embargoed country or jurisdiction.\nentity_types:\n- type: individual\n  text: the individual or entity accessing or using the Services (“Customer,” “you,” or “your”)\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, organization, or other entity, you represent\n    that you have authority to bind that entity\n\
  restricted_uses:\n- summary: Export restrictions\n  text: Each party will comply with the export laws and regulations of the United States, the European Union, and\n    other applicable jurisdictions.\n- summary: Sensitive data\n  text: Customer will not use the Services to transmit to BuildPulse any financial or medical information, or any\n    sensitive personal data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/buildpulse-io/eligibility/buildpulse-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from BuildPulse's own page on 2026-11-09.
synthetic: false
tags:
- CI
- DevOps
- Testing
- Artificial Intelligence
- Analytics
- Company
---
