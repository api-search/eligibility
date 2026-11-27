---
api_specs:
- filename: syncly-health-api-openapi.yml
  format: yaml
  label: Syncly Health API
  slug: syncly-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syncly/openapi/syncly-health-api-openapi.yml
- filename: syncly-well-known-api-openapi.yml
  format: yaml
  label: Syncly .well Known API
  slug: syncly-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syncly/openapi/syncly-well-known-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “User” means any individual or entity that has accepted these Terms and uses the Service.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful purposes
    text: The application is for unlawful purposes
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Agreement is formed when a User accepts these Terms and the Company approves the application.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Syncly
provenance_date: '2026-11-10'
provider_name: Syncly
provider_slug: syncly
slug: syncly-eligibility
source_date: '2026-11-10'
source_filename: syncly-eligibility.yml
source_heading: Eligibility
source_page: https://syncly.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Syncly\naid: syncly\nurl: https://syncly.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “User” means any individual or entity that has accepted these Terms and uses the Service.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: The application is for unlawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Agreement is formed when a User accepts these Terms and the Company approves the application.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/syncly/eligibility/syncly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Syncly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Intelligence
- Social Listening
- Customer Feedback
- Voice of Customer
- Creator Marketing
- Analytics
- Artificial Intelligence
- MCP
---
