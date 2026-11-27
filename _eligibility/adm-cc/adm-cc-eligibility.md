---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To use our Service, you must: Be at least 18 years old'
    type: individual
  - text: Have the authority to enter into these Terms
    type: business
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use the Service for any illegal purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access certain features, you must create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ADM
provenance_date: '2026-11-09'
provider_name: ADM
provider_slug: adm-cc
slug: adm-cc-eligibility
source_date: '2026-11-09'
source_filename: adm-cc-eligibility.yml
source_heading: Eligibility
source_page: https://adm.cc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ADM\naid: adm-cc\nurl: https://adm.cc/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To use our Service, you must: Be at least 18 years old'\n- type: business\n  text: Have the authority to enter into these Terms\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the Service for any illegal purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access certain features, you must create an account.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/adm-cc/eligibility/adm-cc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ADM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Marketing
- Google Ads
- MCP
---
