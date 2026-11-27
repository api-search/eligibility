---
api_specs:
- filename: snov-io-email-verification-api-openapi.yml
  format: yaml
  label: Snov.io Email Verification API
  slug: snovio-email-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snov-io/openapi/snov-io-email-verification-api-openapi.yml
- filename: snov-io-campaigns-api-openapi.yml
  format: yaml
  label: Snov.io Campaigns API
  slug: snovio-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snov-io/openapi/snov-io-campaigns-api-openapi.yml
- filename: snov-io-email-warm-up-api-openapi.yml
  format: yaml
  label: Snov.io Email Warm-up API
  slug: snovio-email-warm-up-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snov-io/openapi/snov-io-email-warm-up-api-openapi.yml
- filename: snov-io-webhooks-api-openapi.yml
  format: yaml
  label: Snov.io Webhooks API
  slug: snovio-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snov-io/openapi/snov-io-webhooks-api-openapi.yml
- filename: snov-io-openapi-generated.yml
  format: yaml
  label: Snov.io API
  slug: snov-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snov-io/openapi/_ae-authored/snov-io-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Customer/User: The person or entity contracting with Snov.io under these Terms and Conditions.'
    type: business
  minimum_age:
    text: By registering as a User of the Snov.io platform, you are indicating that you have read and agree to the Terms and Conditions and that you have legal age or authority to bind yourself or the company.
    value: null
  restricted_uses:
  - summary: Unsolicited commercial email and spam
    text: You are forbidden to distribute unsolicited commercial emails, unsolicited bulk, spam emails, or perform any other kind of email fraud via our Unlimited Email Tracker extension.
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
name: Snov.io
provenance_date: '2026-11-10'
provider_name: Snov.io
provider_slug: snov-io
slug: snov-io-eligibility
source_date: '2026-11-10'
source_filename: snov-io-eligibility.yml
source_heading: Eligibility
source_page: https://snov.io/t_and_c
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snov.io\naid: snov-io\nurl: https://snov.io/t_and_c\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Customer/User: The person or entity contracting with Snov.io under these Terms and Conditions.'\nrestricted_uses:\n- summary: Unsolicited commercial email and spam\n  text: You are forbidden to distribute unsolicited commercial emails, unsolicited bulk, spam emails, or perform\n    any other kind of email fraud via our Unlimited Email Tracker extension.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: By registering as a User of the Snov.io platform, you are indicating that you have read and agree to the\n    Terms and Conditions and that you have legal age or authority to bind yourself or the company.\n"
source_yaml_url: https://artifacts.apis.io/snov-io/eligibility/snov-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Snov.io's own page on 2026-11-10.
synthetic: false
tags:
- Sales Automation
- Email Finder
- Email Verification
- Lead Generation
- Drip Campaigns
- CRM
- LinkedIn Automation
- Prospect Management
- Data Enrichment
- Cold Email
---
