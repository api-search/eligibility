---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: This site is available to members under Australian jurisdiction.
  entity_types:
  - text: This website is designed for use by Australian residents.
    type: individual
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You are responsible for keeping your account details secure. Protect your password and keep it secret.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aware Super
provenance_date: '2026-11-09'
provider_name: Aware Super
provider_slug: aware-super
slug: aware-super-eligibility
source_date: '2026-11-09'
source_filename: aware-super-eligibility.yml
source_heading: Eligibility
source_page: https://aware.com.au/member/about-us/legal/conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aware Super\naid: aware-super\nurl: https://aware.com.au/member/about-us/legal/conditions-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: This site is available to members under Australian jurisdiction.\nentity_types:\n- type: individual\n  text: This website is designed for use by Australian residents.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You are responsible for keeping your account details secure. Protect your password and keep it secret.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aware-super/eligibility/aware-super-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Aware Super's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Superannuation
- Retirement
- Financial Services
- Investment
- Australia
---
