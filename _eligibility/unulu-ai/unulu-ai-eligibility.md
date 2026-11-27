---
api_specs:
- filename: unulu-ai-claims-api-openapi.yml
  format: yaml
  label: unulu-ai Claims API
  slug: unulu-ai-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unulu-ai/openapi/unulu-ai-claims-api-openapi.yml
- filename: unulu-ai-feature-votes-api-openapi.yml
  format: yaml
  label: unulu-ai Feature Votes API
  slug: unulu-ai-feature-votes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unulu-ai/openapi/unulu-ai-feature-votes-api-openapi.yml
- filename: unulu-ai-sites-api-openapi.yml
  format: yaml
  label: unulu-ai Sites API
  slug: unulu-ai-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unulu-ai/openapi/unulu-ai-sites-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service on behalf of an organisation, you represent that you have the authority to bind that organisation to these terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old (or the age of digital consent in your jurisdiction) to use unulu™.
    value: '13'
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
name: unulu-ai
provenance_date: '2026-11-10'
provider_name: unulu-ai
provider_slug: unulu-ai
slug: unulu-ai-eligibility
source_date: '2026-11-10'
source_filename: unulu-ai-eligibility.yml
source_heading: Eligibility
source_page: https://unulu.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: unulu-ai\naid: unulu-ai\nurl: https://unulu.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service on behalf of an organisation, you represent that you have the authority to bind that\n    organisation to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or the age of digital consent in your jurisdiction) to use unulu™.\n"
source_yaml_url: https://artifacts.apis.io/unulu-ai/eligibility/unulu-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from unulu-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Link-in-bio
- MCP
---
