---
api_specs:
- filename: acruxcore-account-api-openapi.yml
  format: yaml
  label: Acrux Core Account API
  slug: acruxcore-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-account-api-openapi.yml
- filename: acruxcore-acrux-core-api-api-openapi.yml
  format: yaml
  label: Acrux Core Acrux Core API
  slug: acruxcore-acrux-core-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-acrux-core-api-api-openapi.yml
- filename: acruxcore-prompts-api-openapi.yml
  format: yaml
  label: Acrux Core Prompts API
  slug: acruxcore-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-prompts-api-openapi.yml
- filename: acruxcore-tools-api-openapi.yml
  format: yaml
  label: Acrux Core Tools API
  slug: acruxcore-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-tools-api-openapi.yml
- filename: acruxcore-traces-api-openapi.yml
  format: yaml
  label: Acrux Core Traces API
  slug: acruxcore-traces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-traces-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be able to form a binding contract to use the Service.
    value: null
  restricted_uses:
  - summary: Unlawful or rights-infringing use
    text: Break the law or infringe others' rights using the Service.
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
name: Acrux Core
provenance_date: '2026-11-09'
provider_name: Acrux Core
provider_slug: acruxcore
slug: acruxcore-eligibility
source_date: '2026-11-09'
source_filename: acruxcore-eligibility.yml
source_heading: Eligibility
source_page: https://acruxcore.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acrux Core\naid: acruxcore\nurl: https://acruxcore.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or rights-infringing use\n  text: Break the law or infringe others' rights using the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/acruxcore/eligibility/acruxcore-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Acrux Core's own page on 2026-11-09.
synthetic: false
tags:
- LLMOps
- Open Source
- Platform
- Engineering
- Artificial Intelligence
---
