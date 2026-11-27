---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Service on behalf of a business or corporate entity (“Organization”), then you hereby represent and warrant that you have the authority to bind that Organization
    type: business
  minimum_age:
    text: THE SERVICE IS NOT FOR PERSONS UNDER THE AGE OF 18
    value: '18'
  restricted_uses:
  - summary: Investor Portal access limited to invited investors
    text: You may only create an Account and access the Investor Portal once you have been invited to do so by Bitwise in its sole discretion.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Bitwise reserves the right to reject any application for membership and Investor Information Request Form at any time for any reason or for no reason at all
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bitwiseassetmanagement
provenance_date: '2026-11-09'
provider_name: Bitwiseassetmanagement
provider_slug: bitwiseassetmanagement
slug: bitwiseassetmanagement-eligibility
source_date: '2026-11-09'
source_filename: bitwiseassetmanagement-eligibility.yml
source_heading: Eligibility
source_page: https://bitwiseinvestments.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitwiseassetmanagement\naid: bitwiseassetmanagement\nurl: https://bitwiseinvestments.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Service on behalf of a business or corporate entity (“Organization”), then you\n    hereby represent and warrant that you have the authority to bind that Organization\nrestricted_uses:\n- summary: Investor Portal access limited to invited investors\n  text: You may only create an Account and access the Investor Portal once you have been invited to do so by Bitwise\n\
  \    in its sole discretion.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Bitwise reserves the right to reject any application for membership and Investor Information Request Form\n    at any time for any reason or for no reason at all\nminimum_age:\n  value: '18'\n  text: THE SERVICE IS NOT FOR PERSONS UNDER THE AGE OF 18\n"
source_yaml_url: https://artifacts.apis.io/bitwiseassetmanagement/eligibility/bitwiseassetmanagement-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bitwiseassetmanagement's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- ETFs
- Investment
- Asset Management
---
