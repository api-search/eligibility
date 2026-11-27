---
api_specs:
- filename: humanloop-datasets-api-openapi.yml
  format: yaml
  label: Humanloop Datasets API
  slug: humanloop-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-datasets-api-openapi.yml
- filename: humanloop-evaluators-api-openapi.yml
  format: yaml
  label: Humanloop Evaluators API
  slug: humanloop-evaluators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-evaluators-api-openapi.yml
- filename: humanloop-logs-api-openapi.yml
  format: yaml
  label: Humanloop Logs API
  slug: humanloop-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-logs-api-openapi.yml
- filename: humanloop-prompts-api-openapi.yml
  format: yaml
  label: Humanloop Prompts API
  slug: humanloop-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-prompts-api-openapi.yml
- filename: humanloop-sessions-api-openapi.yml
  format: yaml
  label: Humanloop Sessions API
  slug: humanloop-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-sessions-api-openapi.yml
- filename: humanloop-tools-api-openapi.yml
  format: yaml
  label: Humanloop Tools API
  slug: humanloop-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/humanloop/openapi/humanloop-tools-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The page does not list served or excluded countries; the Supplier is a company incorporated in England and Wales.
  entity_types:
  - text: The Services are intended for business use only.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: access, store, distribute or transmit any Viruses or any material during its use of the Software that is unlawful, harmful, infringing, offensive, discriminatory, or which facilitates illegal activity
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
name: Humanloop
provenance_date: '2026-11-09'
provider_name: Humanloop
provider_slug: humanloop
slug: humanloop-eligibility
source_date: '2026-11-09'
source_filename: humanloop-eligibility.yml
source_heading: Eligibility
source_page: https://humanloop.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Humanloop\naid: humanloop\nurl: https://humanloop.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The page does not list served or excluded countries; the Supplier is a company incorporated in England and\n    Wales.\nentity_types:\n- type: business\n  text: The Services are intended for business use only.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: access, store, distribute or transmit any Viruses or any material during its use of the Software that is\n    unlawful, harmful, infringing, offensive, discriminatory, or which facilitates\
  \ illegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/humanloop/eligibility/humanloop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Humanloop's own page on 2026-11-09.
synthetic: false
tags:
- LLM Platform
- Prompt Management
- Evaluation
- LLMOps
- Observability
- Datasets
- Prompts
- Tools
- Logs
- Multi-Provider
- Sunsetting
- Acquired
---
