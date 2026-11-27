---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: the information is not intended for those users who act under other jurisdictions of other states that require compliance with different requirements
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent purposes
    text: the User agrees not to use the Website for fraudulent purposes
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
name: BBVA
provenance_date: '2026-11-09'
provider_name: BBVA
provider_slug: bbvaapimarket
slug: bbvaapimarket-eligibility
source_date: '2026-11-09'
source_filename: bbvaapimarket-eligibility.yml
source_heading: Eligibility
source_page: https://www.bbvaapimarket.com/en/legal-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BBVA\naid: bbvaapimarket\nurl: https://www.bbvaapimarket.com/en/legal-notice/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: the information is not intended for those users who act under other jurisdictions of other states that require\n    compliance with different requirements\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent purposes\n  text: the User agrees not to use the Website for fraudulent purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bbvaapimarket/eligibility/bbvaapimarket-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from BBVA's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Open Banking
- Finance
- Payments
- API Platform
---
