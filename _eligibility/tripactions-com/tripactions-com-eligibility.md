---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant to Navan that if you are an individual (i.e., not a corporation) you are at least 18 years of age.
    type: individual
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind such entity to these Terms
    type: business
  minimum_age:
    text: if you are an individual (i.e., not a corporation) you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: solely for your personal, non-commercial purposes
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
name: Navan
provenance_date: '2026-11-10'
provider_name: Navan
provider_slug: tripactions-com
slug: tripactions-com-eligibility
source_date: '2026-11-10'
source_filename: tripactions-com-eligibility.yml
source_heading: Eligibility
source_page: https://navan.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Navan\naid: tripactions-com\nurl: https://navan.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant to Navan that if you are an individual (i.e., not a corporation) you are at least\n    18 years of age.\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent and warrant\n    that you have the authority to bind such entity to these Terms\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: solely for your personal,\
  \ non-commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are an individual (i.e., not a corporation) you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/tripactions-com/eligibility/tripactions-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Navan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Travel
- Expense Management
- Software-as-a-Service
- Corporate
---
