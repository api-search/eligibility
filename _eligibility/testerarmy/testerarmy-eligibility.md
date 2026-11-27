---
api_specs:
- filename: testerarmy-groups-api-openapi.yml
  format: yaml
  label: Testerarmy Groups API
  slug: testerarmy-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-groups-api-openapi.yml
- filename: testerarmy-projects-api-openapi.yml
  format: yaml
  label: Testerarmy Projects API
  slug: testerarmy-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-projects-api-openapi.yml
- filename: testerarmy-test-runs-api-openapi.yml
  format: yaml
  label: Testerarmy Test Runs API
  slug: testerarmy-test-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-test-runs-api-openapi.yml
- filename: testerarmy-tests-api-openapi.yml
  format: yaml
  label: Testerarmy Tests API
  slug: testerarmy-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-tests-api-openapi.yml
- filename: testerarmy-webhooks-api-openapi.yml
  format: yaml
  label: Testerarmy Webhooks API
  slug: testerarmy-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/testerarmy/openapi/testerarmy-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to use the Service.
    type: individual
  - text: have the authority to enter into these Terms on behalf of yourself or your organization
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Unauthorized website testing
    text: Test websites you do not own or do not have explicit authorization to test
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must create an account using Google OAuth, GitHub OAuth, or email magic link.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Testerarmy
provenance_date: '2026-11-10'
provider_name: Testerarmy
provider_slug: testerarmy
slug: testerarmy-eligibility
source_date: '2026-11-10'
source_filename: testerarmy-eligibility.yml
source_heading: Eligibility
source_page: https://tester.army/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Testerarmy\naid: testerarmy\nurl: https://tester.army/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use the Service.\n- type: business\n  text: have the authority to enter into these Terms on behalf of yourself or your organization\nrestricted_uses:\n- summary: Unauthorized website testing\n  text: Test websites you do not own or do not have explicit authorization to test\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must create an account using Google\
  \ OAuth, GitHub OAuth, or email magic link.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/testerarmy/eligibility/testerarmy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Testerarmy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- QA
- Software Testing
- Browser Automation
- AI Agents
- Developer Tools
- CI/CD
- End-to-End Testing
- Mobile Testing
---
