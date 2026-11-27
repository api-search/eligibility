---
api_specs:
- filename: 4dayweek-io-4dayweek-io-public-api-api-openapi.yml
  format: yaml
  label: 4dayweek-io 4dayweek.io Public API
  slug: 4dayweek-io-4dayweek-io-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/4dayweek-io/openapi/4dayweek-io-4dayweek-io-public-api-api-openapi.yml
- filename: 4dayweek-io-jobs-api-openapi.yml
  format: yaml
  label: 4dayweek-io Jobs API
  slug: 4dayweek-io-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/4dayweek-io/openapi/4dayweek-io-jobs-api-openapi.yml
- filename: 4dayweek-io-mcp-api-openapi.yml
  format: yaml
  label: 4dayweek-io MCP API
  slug: 4dayweek-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/4dayweek-io/openapi/4dayweek-io-mcp-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years of age. If you are under 18, you confirm that you have obtained the consent of a parent or legal guardian to use the Service.
    type: individual
  - text: If you are registering an account on behalf of a company or organisation (an "Employer Account"), you represent and warrant that you are duly authorised to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Using the Service for any purpose that is unlawful, fraudulent, or harmful, or in connection with any unlawful, fraudulent, or harmful activity.
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
name: 4dayweek-io
provenance_date: '2026-11-09'
provider_name: 4dayweek-io
provider_slug: 4dayweek-io
slug: 4dayweek-io-eligibility
source_date: '2026-11-09'
source_filename: 4dayweek-io-eligibility.yml
source_heading: Eligibility
source_page: https://4dayweek.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 4dayweek-io\naid: 4dayweek-io\nurl: https://4dayweek.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years of age. If you are under 18, you confirm that you have obtained the consent\n    of a parent or legal guardian to use the Service.\n- type: business\n  text: If you are registering an account on behalf of a company or organisation (an \"Employer Account\"), you represent\n    and warrant that you are duly authorised to bind that entity to these Terms\nrestricted_uses:\n- summary: Unlawful or harmful\
  \ use\n  text: Using the Service for any purpose that is unlawful, fraudulent, or harmful, or in connection with any unlawful,\n    fraudulent, or harmful activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/4dayweek-io/eligibility/4dayweek-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from 4dayweek-io's own page on 2026-11-09.
synthetic: false
tags:
- Remote Jobs
- Flexible Schedule
- Work-Life Balance
- Recruiting
---
