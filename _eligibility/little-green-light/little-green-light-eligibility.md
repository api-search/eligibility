---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - EU
    - UK
    - CH
    served: []
    text: No LGL accounts for organizations based in the EU, UK or Switzerland. Little Green Light Accounts (“LGL Accounts”) are not available to organizations based in the EU, UK or Switzerland.
  entity_types:
  - text: You must provide your legal full name, a valid email address, and any other information requested in order to complete the signup process and activate your subscription
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive personal information
    text: You should not provide “sensitive personal information” about Users’ medical or health conditions, racial or ethnic origin, ideological views, political opinions, religious or philosophical beliefs
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- EU
- UK
- CH
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Little Green Light
provenance_date: '2026-11-09'
provider_name: Little Green Light
provider_slug: little-green-light
slug: little-green-light-eligibility
source_date: '2026-11-09'
source_filename: little-green-light-eligibility.yml
source_heading: Eligibility
source_page: https://www.littlegreenlight.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Little Green Light\naid: little-green-light\nurl: https://www.littlegreenlight.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - EU\n  - UK\n  - CH\n  text: No LGL accounts for organizations based in the EU, UK or Switzerland. Little Green Light Accounts (“LGL\n    Accounts”) are not available to organizations based in the EU, UK or Switzerland.\nentity_types:\n- type: business\n  text: You must provide your legal full name, a valid email address, and any other information requested in order\n    to complete the signup process and activate your subscription\nrestricted_uses:\n\
  - summary: Sensitive personal information\n  text: You should not provide “sensitive personal information” about Users’ medical or health conditions, racial\n    or ethnic origin, ideological views, political opinions, religious or philosophical beliefs\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/little-green-light/eligibility/little-green-light-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Little Green Light's own page on 2026-11-09.
synthetic: false
tags:
- Donor Management
- Nonprofit Software
- Fundraising
- Online Donations
- Data Management
---
