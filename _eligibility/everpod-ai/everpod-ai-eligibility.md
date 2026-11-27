---
api_specs:
- filename: everpod-ai-openapi-generated.yml
  format: yaml
  label: Everpod API
  slug: everpod-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everpod-ai/openapi/_ae-authored/everpod-ai-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country or on a list where U.S. sanctions or export controls prohibit your use of the service
  minimum_age:
    text: You must be at least 18 years old to use Everpod.
    value: '18'
  restricted_uses:
  - summary: No regulated-industry workloads
    text: the service is not offered for workloads that require sector-specific compliance regimes (such as processing payment-card data)
  - summary: Export and sanctions
    text: use the service where prohibited by applicable sanctions or export-control laws, or for any prohibited end use
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
name: Everpod
provenance_date: '2026-11-09'
provider_name: Everpod
provider_slug: everpod-ai
slug: everpod-ai-eligibility
source_date: '2026-11-09'
source_filename: everpod-ai-eligibility.yml
source_heading: Eligibility
source_page: https://everpod.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Everpod\naid: everpod-ai\nurl: https://everpod.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country or on a list where U.S. sanctions or export controls\n    prohibit your use of the service\nentity_types: []\nrestricted_uses:\n- summary: No regulated-industry workloads\n  text: the service is not offered for workloads that require sector-specific compliance regimes (such as processing\n    payment-card data)\n- summary: Export and sanctions\n  text: use the service where prohibited by applicable sanctions or export-control\
  \ laws, or for any prohibited end\n    use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use Everpod.\n"
source_yaml_url: https://artifacts.apis.io/everpod-ai/eligibility/everpod-ai-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Everpod's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Cloud Computing
- Developer Tools
- Platform
- Agents
---
