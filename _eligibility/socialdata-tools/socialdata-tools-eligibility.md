---
api_specs:
- filename: socialdata-tools-data-api-api-openapi.yml
  format: yaml
  label: socialdata-tools Data API
  slug: socialdata-tools-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialdata-tools/openapi/socialdata-tools-data-api-api-openapi.yml
- filename: socialdata-tools-monitoring-api-api-openapi.yml
  format: yaml
  label: socialdata-tools Monitoring API
  slug: socialdata-tools-monitoring-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialdata-tools/openapi/socialdata-tools-monitoring-api-api-openapi.yml
- filename: socialdata-tools-social-actions-api-api-openapi.yml
  format: yaml
  label: socialdata-tools Social Actions API
  slug: socialdata-tools-social-actions-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialdata-tools/openapi/socialdata-tools-social-actions-api-api-openapi.yml
- filename: socialdata-tools-socialdata-account-management-api-openapi.yml
  format: yaml
  label: socialdata-tools SocialData Account Management API
  slug: socialdata-tools-socialdata-account-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialdata-tools/openapi/socialdata-tools-socialdata-account-management-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act on behalf of a company when accepting these Terms and the Privacy Policy, you also hereby declare to be authorized to perform such legal actions on behalf of the company
    type: business
  minimum_age:
    text: you claim that you are over 18 years old
    value: '18'
  restricted_uses:
  - summary: Only publicly accessible or authorised sources
    text: The Website or Services functionalities may be used solely on such publicly accessible websites or other sources where their use (including data extraction) is permitted explicitly or where you are authorised to do so.
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
name: socialdata-tools
provenance_date: '2026-11-10'
provider_name: socialdata-tools
provider_slug: socialdata-tools
slug: socialdata-tools-eligibility
source_date: '2026-11-10'
source_filename: socialdata-tools-eligibility.yml
source_heading: Eligibility
source_page: https://socialdata.tools/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: socialdata-tools\naid: socialdata-tools\nurl: https://socialdata.tools/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act on behalf of a company when accepting these Terms and the Privacy Policy, you also hereby declare\n    to be authorized to perform such legal actions on behalf of the company\nrestricted_uses:\n- summary: Only publicly accessible or authorised sources\n  text: The Website or Services functionalities may be used solely on such publicly accessible websites or other\n    sources where\
  \ their use (including data extraction) is permitted explicitly or where you are authorised to do\n    so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you claim that you are over 18 years old\n"
source_yaml_url: https://artifacts.apis.io/socialdata-tools/eligibility/socialdata-tools-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from socialdata-tools's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- Data
- Public APIs
---
