---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use your Services for personal banking needs only.
    type: individual
  - text: You may not conduct activities related to the conduct of any business, even if that business is a sole proprietorship.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use only
    text: You may use your Services for personal banking needs only.
  - summary: No use on behalf of others
    text: you will not use your Services on behalf of another person, except with Meridian’s prior written consent.
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
name: Meridian Credit Union
provenance_date: '2026-11-10'
provider_name: Meridian Credit Union
provider_slug: meridian-credit-union
slug: meridian-credit-union-eligibility
source_date: '2026-11-10'
source_filename: meridian-credit-union-eligibility.yml
source_heading: Eligibility
source_page: https://www.meridiancu.ca/about-meridian/legal/personal-membership-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meridian Credit Union\naid: meridian-credit-union\nurl: https://www.meridiancu.ca/about-meridian/legal/personal-membership-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use your Services for personal banking needs only.\n- type: business\n  text: You may not conduct activities related to the conduct of any business, even if that business is a sole proprietorship.\nrestricted_uses:\n- summary: Personal use only\n  text: You may use your Services for personal banking needs only.\n- summary: No use\
  \ on behalf of others\n  text: you will not use your Services on behalf of another person, except with Meridian’s prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/meridian-credit-union/eligibility/meridian-credit-union-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Meridian Credit Union's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- Canada
- Credit Union
- Cooperative
- Ontario
---
