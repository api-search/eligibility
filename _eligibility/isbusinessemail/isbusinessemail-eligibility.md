---
api_specs:
- filename: isbusinessemail-check-api-openapi.yml
  format: yaml
  label: isBusinessEmail Check API
  slug: isbusinessemail-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isbusinessemail/openapi/isbusinessemail-check-api-openapi.yml
- filename: isbusinessemail-feedback-api-openapi.yml
  format: yaml
  label: isBusinessEmail Feedback API
  slug: isbusinessemail-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isbusinessemail/openapi/isbusinessemail-feedback-api-openapi.yml
- filename: isbusinessemail-health-api-openapi.yml
  format: yaml
  label: isBusinessEmail Health API
  slug: isbusinessemail-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isbusinessemail/openapi/isbusinessemail-health-api-openapi.yml
- filename: isbusinessemail-usage-api-openapi.yml
  format: yaml
  label: isBusinessEmail Usage API
  slug: isbusinessemail-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/isbusinessemail/openapi/isbusinessemail-usage-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to create an account.
    type: individual
  - text: If you use the Service for an organization, you confirm that you’re authorized to accept these Terms for it, and “you” includes that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old to create an account.
    value: '16'
  restricted_uses:
  - summary: Special categories of personal data
    text: submit special categories of personal data or anything other than email addresses and domains you’re checking
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
name: isBusinessEmail
provenance_date: '2026-11-09'
provider_name: isBusinessEmail
provider_slug: isbusinessemail
slug: isbusinessemail-eligibility
source_date: '2026-11-09'
source_filename: isbusinessemail-eligibility.yml
source_heading: Eligibility
source_page: https://isbusinessemail.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: isBusinessEmail\naid: isbusinessemail\nurl: https://isbusinessemail.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to create an account.\n- type: business\n  text: If you use the Service for an organization, you confirm that you’re authorized to accept these Terms for\n    it, and “you” includes that organization.\nrestricted_uses:\n- summary: Special categories of personal data\n  text: submit special categories of personal data or anything other than email addresses and domains you’re\
  \ checking\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/isbusinessemail/eligibility/isbusinessemail-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from isBusinessEmail's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Verification
- BusinessTools
- EU-hosted
---
