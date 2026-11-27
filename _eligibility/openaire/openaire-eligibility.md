---
api_specs:
- filename: openaire-broker-api-openapi.yml
  format: yaml
  label: OpenAIRE Broker API
  slug: openaire-broker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openaire/openapi/openaire-broker-api-openapi.yml
- filename: openaire-oidc-api-openapi.yml
  format: yaml
  label: OpenAIRE Oidc API
  slug: openaire-oidc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openaire/openapi/openaire-oidc-api-openapi.yml
- filename: openaire-openaire-api-api-openapi.yml
  format: yaml
  label: OpenAIRE OpenAIRE API
  slug: openaire-openaire-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openaire/openapi/openaire-openaire-api-api-openapi.yml
- filename: openaire-skg-if-api-openapi.yml
  format: yaml
  label: OpenAIRE Skg If API
  slug: openaire-skg-if-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openaire/openapi/openaire-skg-if-api-openapi.yml
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
  - summary: Lawful purposes only
    text: You shall only use the Services for lawful purposes and not breach, attempt to breach, nor circumvent administrative or security controls.
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
name: OpenAIRE
provenance_date: '2026-11-10'
provider_name: OpenAIRE
provider_slug: openaire
slug: openaire-eligibility
source_date: '2026-11-10'
source_filename: openaire-eligibility.yml
source_heading: Eligibility
source_page: https://www.openaire.eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenAIRE\naid: openaire\nurl: https://www.openaire.eu/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You shall only use the Services for lawful purposes and not breach, attempt to breach, nor circumvent administrative\n    or security controls.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openaire/eligibility/openaire-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from OpenAIRE's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Open Science
- Research Infrastructure
- Europe
- Services
---
