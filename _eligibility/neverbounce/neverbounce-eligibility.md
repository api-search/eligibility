---
api_specs:
- filename: neverbounce-account-api-openapi.yml
  format: yaml
  label: NeverBounce Account API
  slug: neverbounce-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neverbounce/openapi/neverbounce-account-api-openapi.yml
- filename: neverbounce-jobs-api-openapi.yml
  format: yaml
  label: NeverBounce Jobs API
  slug: neverbounce-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neverbounce/openapi/neverbounce-jobs-api-openapi.yml
- filename: neverbounce-single-api-openapi.yml
  format: yaml
  label: NeverBounce Single API
  slug: neverbounce-single-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neverbounce/openapi/neverbounce-single-api-openapi.yml
- filename: neverbounce-poe-api-openapi.yml
  format: yaml
  label: NeverBounce POE API
  slug: neverbounce-poe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neverbounce/openapi/neverbounce-poe-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are or have been duly authorized by your employer, as applicable, to (i) sign up for NeverBounce and accept these Terms
    type: business
  minimum_age:
    text: When you create an account with us, you represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Business-to-business purposes only
    text: You agree not to use NeverBounce for any purpose except for business-to-business sales, marketing, recruiting, or business development.
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
name: NeverBounce
provenance_date: '2026-11-10'
provider_name: NeverBounce
provider_slug: neverbounce
slug: neverbounce-eligibility
source_date: '2026-11-10'
source_filename: neverbounce-eligibility.yml
source_heading: Eligibility
source_page: https://www.neverbounce.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NeverBounce\naid: neverbounce\nurl: https://www.neverbounce.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You are or have been duly authorized by your employer, as applicable, to (i) sign up for NeverBounce and\n    accept these Terms\nrestricted_uses:\n- summary: Business-to-business purposes only\n  text: You agree not to use NeverBounce for any purpose except for business-to-business sales, marketing, recruiting,\n    or business development.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/neverbounce/eligibility/neverbounce-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from NeverBounce's own page on 2026-11-10.
synthetic: false
tags:
- Email Verification
- Email Hygiene
- Deliverability
- Marketing
- List Cleaning
- Data Quality
- ZoomInfo
- Email
---
