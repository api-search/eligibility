---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: This site is intended for visitors from Canada only
  minimum_age:
    text: who have reached the age of majority in their jurisdiction of residence
    value: age of majority
  restricted_uses:
  - summary: Impersonation
    text: You agree not to impersonate another person in your use of the site
  - source: https://www.economical.com/en/terms-of-use
    summary: Impersonation
    text: You agree not to impersonate another person in your use of the site
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We reserve the right, in our sole and absolute discretion, to require proof of identity (in a form acceptable to Sonnet)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Definity Financial
provenance_date: '2026-11-09'
provider_name: Definity Financial
provider_slug: definity-financial
slug: definity-financial-eligibility
source_date: '2026-11-09'
source_filename: definity-financial-eligibility.yml
source_heading: Eligibility
source_page: https://www.sonnet.ca/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Definity Financial\naid: definity-financial\nurl: https://www.sonnet.ca/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.economical.com/en/terms-of-use\n  - https://www.sonnet.ca/terms-of-use\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: This site is intended for visitors from Canada only\nentity_types: []\nrestricted_uses:\n- summary: Impersonation\n  text: You agree not to impersonate another person in your use of the site\n- summary: Impersonation\n  text: You agree not to impersonate another person in your use of the site\n  source: https://www.economical.com/en/terms-of-use\n\
  verification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We reserve the right, in our sole and absolute discretion, to require proof of identity (in a form acceptable\n    to Sonnet)\nminimum_age:\n  value: age of majority\n  text: who have reached the age of majority in their jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/definity-financial/eligibility/definity-financial-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Definity Financial's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Canada
- Property and Casualty
- Carrier
- Underwriting
- Claims
- Pet Insurance
- Direct to Consumer
- CSIO
- Insurtech
---
