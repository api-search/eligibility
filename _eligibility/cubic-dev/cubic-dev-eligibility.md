---
api_specs:
- filename: cubic-dev-analytics-api-openapi.yml
  format: yaml
  label: cubic Analytics API
  slug: cubic-dev-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cubic-dev/openapi/cubic-dev-analytics-api-openapi.yml
- filename: cubic-dev-organizations-api-openapi.yml
  format: yaml
  label: cubic Organizations API
  slug: cubic-dev-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cubic-dev/openapi/cubic-dev-organizations-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least the age of majority in your jurisdiction (e.g., 18 years old in the U.S.) or older to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: you represent and warrant that you are at least 18 years old or the age of majority, whichever is higher.
    value: '18'
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
name: cubic
provenance_date: '2026-11-09'
provider_name: cubic
provider_slug: cubic-dev
slug: cubic-dev-eligibility
source_date: '2026-11-09'
source_filename: cubic-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.cubic.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: cubic\naid: cubic-dev\nurl: https://www.cubic.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your jurisdiction (e.g., 18 years old in the U.S.) or older\n    to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: you represent and warrant that you are at least 18 years old or the age of majority, whichever is higher.\n"
source_yaml_url: https://artifacts.apis.io/cubic-dev/eligibility/cubic-dev-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from cubic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Code Review
- Developer Tools
- GitHub
- Pull Requests
- MCP
- Analytics
---
