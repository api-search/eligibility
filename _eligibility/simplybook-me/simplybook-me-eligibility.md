---
api_specs:
- filename: simplybook-me-openapi-generated.yml
  format: yaml
  label: SimplyBook.me API
  slug: simplybook-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplybook-me/openapi/_ae-authored/simplybook-me-openapi-generated.yml
- filename: simplybook-me-admin-api-openapi.yml
  format: yaml
  label: SimplyBook.me Admin API
  slug: simplybook-me-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simplybook-me/openapi/simplybook-me-admin-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years old when creating an Account
    type: individual
  - text: The right of withdrawal does not apply to subscribers who do not contract as consumers, including business, enterprise and professional Users.
    type: business
  minimum_age:
    text: You are at least 18 years old when creating an Account
    value: '18'
  restricted_uses:
  - summary: Spam and unsolicited messages
    text: sending spams and/or other emails or SMS (text messages)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: when you create an Account, You must provide specific information about yourself
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SimplyBook.me
provenance_date: '2026-11-10'
provider_name: SimplyBook.me
provider_slug: simplybook-me
slug: simplybook-me-eligibility
source_date: '2026-11-10'
source_filename: simplybook-me-eligibility.yml
source_heading: Eligibility
source_page: https://simplybook.me/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SimplyBook.me\naid: simplybook-me\nurl: https://simplybook.me/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years old when creating an Account\n- type: business\n  text: The right of withdrawal does not apply to subscribers who do not contract as consumers, including business,\n    enterprise and professional Users.\nrestricted_uses:\n- summary: Spam and unsolicited messages\n  text: sending spams and/or other emails or SMS (text messages)\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: when you create an Account, You must provide specific information about yourself\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old when creating an Account\n"
source_yaml_url: https://artifacts.apis.io/simplybook-me/eligibility/simplybook-me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from SimplyBook.me's own page on 2026-11-10.
synthetic: false
tags:
- Scheduling
- Software-as-a-Service
- Booking
- Integration
- Automation
---
