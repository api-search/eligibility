---
api_specs:
- filename: anchorregistry-ai-account-api-openapi.yml
  format: yaml
  label: AnchorRegistry Account API
  slug: anchorregistry-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchorregistry-ai/openapi/anchorregistry-ai-account-api-openapi.yml
- filename: anchorregistry-ai-discovery-api-openapi.yml
  format: yaml
  label: AnchorRegistry Discovery API
  slug: anchorregistry-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchorregistry-ai/openapi/anchorregistry-ai-discovery-api-openapi.yml
- filename: anchorregistry-ai-register-api-openapi.yml
  format: yaml
  label: AnchorRegistry Register API
  slug: anchorregistry-ai-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchorregistry-ai/openapi/anchorregistry-ai-register-api-openapi.yml
- filename: anchorregistry-ai-system-api-openapi.yml
  format: yaml
  label: AnchorRegistry System API
  slug: anchorregistry-ai-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchorregistry-ai/openapi/anchorregistry-ai-system-api-openapi.yml
- filename: anchorregistry-ai-verify-api-openapi.yml
  format: yaml
  label: AnchorRegistry Verify API
  slug: anchorregistry-ai-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anchorregistry-ai/openapi/anchorregistry-ai-verify-api-openapi.yml
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
  - summary: No financial instruments or securities
    text: You may not use AnchorRegistry to create, represent, or facilitate financial instruments, payment systems, stored value systems, money transmission services, or securities of any kind.
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
name: AnchorRegistry
provenance_date: '2026-11-09'
provider_name: AnchorRegistry
provider_slug: anchorregistry-ai
slug: anchorregistry-ai-eligibility
source_date: '2026-11-09'
source_filename: anchorregistry-ai-eligibility.yml
source_heading: Eligibility
source_page: https://anchorregistry.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnchorRegistry\naid: anchorregistry-ai\nurl: https://anchorregistry.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No financial instruments or securities\n  text: You may not use AnchorRegistry to create, represent, or facilitate financial instruments, payment systems,\n    stored value systems, money transmission services, or securities of any kind.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anchorregistry-ai/eligibility/anchorregistry-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AnchorRegistry's own page on 2026-11-09.
synthetic: false
tags:
- Provenance
- Onchain
- Artificial Intelligence
- Data
- Artifacts
---
