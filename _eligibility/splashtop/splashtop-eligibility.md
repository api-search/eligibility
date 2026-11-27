---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Materials may not be appropriate or available for use in other locations.
  entity_types:
  - text: Solely for business use if you are an organization or agent of your organization.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Splashtop
provenance_date: '2026-11-10'
provider_name: Splashtop
provider_slug: splashtop
slug: splashtop-eligibility
source_date: '2026-11-10'
source_filename: splashtop-eligibility.yml
source_heading: Eligibility
source_page: https://www.splashtop.com/legal/website-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Splashtop\naid: splashtop\nurl: https://www.splashtop.com/legal/website-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Materials may not be appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: Solely for business use if you are an organization or agent of your organization.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/splashtop/eligibility/splashtop-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Splashtop's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Remote Access
- Remote Support
- Remote Desktop
- Endpoint Management
- IT Management
- MSP
- Security
- Remote Work
---
