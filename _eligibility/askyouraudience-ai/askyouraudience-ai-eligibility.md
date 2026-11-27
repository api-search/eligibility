---
api_specs:
- filename: askyouraudience-ai-openapi-generated.yml
  format: yaml
  label: Ask Your Audience API
  slug: askyouraudience-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askyouraudience-ai/openapi/_ae-authored/askyouraudience-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use AYA for an organisation, you confirm that you can bind that organisation.
    type: business
  minimum_age:
    text: You must be at least 18 and legally able to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: No unlawful, deceptive or discriminatory use
    text: break the law, infringe rights, deceive people, or facilitate discrimination or harm
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
name: Ask Your Audience
provenance_date: '2026-11-09'
provider_name: Ask Your Audience
provider_slug: askyouraudience-ai
slug: askyouraudience-ai-eligibility
source_date: '2026-11-09'
source_filename: askyouraudience-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.askyouraudience.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ask Your Audience\naid: askyouraudience-ai\nurl: https://www.askyouraudience.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use AYA for an organisation, you confirm that you can bind that organisation.\nrestricted_uses:\n- summary: No unlawful, deceptive or discriminatory use\n  text: break the law, infringe rights, deceive people, or facilitate discrimination or harm\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally\
  \ able to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/askyouraudience-ai/eligibility/askyouraudience-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ask Your Audience's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- AudienceResearch
- MarketTesting
- Digital Twin
---
