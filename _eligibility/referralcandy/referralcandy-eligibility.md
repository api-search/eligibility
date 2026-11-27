---
api_specs:
- filename: referralcandy-openapi-generated.yml
  format: yaml
  label: ReferralCandy API
  slug: referralcandy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/referralcandy/openapi/_ae-authored/referralcandy-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must provide your organization’s legal full name, a valid email address, and any other information requested in order to complete the signup process.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: You may not use the Service for any illegal or unauthorized purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Anafore reserves the right to refuse service to anyone for any reason at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ReferralCandy
provenance_date: '2026-11-10'
provider_name: ReferralCandy
provider_slug: referralcandy
slug: referralcandy-eligibility
source_date: '2026-11-10'
source_filename: referralcandy-eligibility.yml
source_heading: Eligibility
source_page: https://www.referralcandy.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ReferralCandy\naid: referralcandy\nurl: https://www.referralcandy.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must provide your organization’s legal full name, a valid email address, and any other information requested\n    in order to complete the signup process.\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: You may not use the Service for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Anafore reserves the right to refuse service\
  \ to anyone for any reason at any time.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/referralcandy/eligibility/referralcandy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ReferralCandy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Referrals
- Affiliates
- E-Commerce
- Marketing
---
