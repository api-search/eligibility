---
api_specs:
- filename: sendar-app-emails-api-openapi.yml
  format: yaml
  label: sendar-app Emails API
  slug: sendar-app-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendar-app/openapi/sendar-app-emails-api-openapi.yml
- filename: sendar-app-headless-api-openapi.yml
  format: yaml
  label: sendar-app Headless API
  slug: sendar-app-headless-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendar-app/openapi/sendar-app-headless-api-openapi.yml
- filename: sendar-app-inboxes-api-openapi.yml
  format: yaml
  label: sendar-app Inboxes API
  slug: sendar-app-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendar-app/openapi/sendar-app-inboxes-api-openapi.yml
- filename: sendar-app-link-checks-api-openapi.yml
  format: yaml
  label: sendar-app Link Checks API
  slug: sendar-app-link-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendar-app/openapi/sendar-app-link-checks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are using the Service on behalf of a company or other organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons or territories
    text: You may not use the Service for the benefit of any sanctioned person or territory
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Certain features — including creating API keys and adding sending domains — require you to first confirm your email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: sendar-app
provenance_date: '2026-11-10'
provider_name: sendar-app
provider_slug: sendar-app
slug: sendar-app-eligibility
source_date: '2026-11-10'
source_filename: sendar-app-eligibility.yml
source_heading: Eligibility
source_page: https://sendar.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: sendar-app\naid: sendar-app\nurl: https://sendar.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are using the Service on behalf of a company or other organization, you represent that you have authority\n    to bind that organization\nrestricted_uses:\n- summary: Sanctioned persons or territories\n  text: You may not use the Service for the benefit of any sanctioned person or territory\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Certain features — including creating API keys and adding sending domains — require you to first confirm\n    your email address.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/sendar-app/eligibility/sendar-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from sendar-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Delivery
- Automation
---
