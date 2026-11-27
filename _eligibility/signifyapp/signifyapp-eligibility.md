---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the Account is created by the legal entity or any other type of organizational entity, it is implied that the respective authorized person is creating such Account/declaring its intent.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal activity or financial pyramid schemes
    text: The Customer will not use the Platform for illegal/unlawful actions;
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
name: Signify
provenance_date: '2026-11-10'
provider_name: Signify
provider_slug: signifyapp
slug: signifyapp-eligibility
source_date: '2026-11-10'
source_filename: signifyapp-eligibility.yml
source_heading: Eligibility
source_page: https://signifyapp.com/en/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Signify\naid: signifyapp\nurl: https://signifyapp.com/en/policies/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the Account is created by the legal entity or any other type of organizational entity, it is implied\n    that the respective authorized person is creating such Account/declaring its intent.\nrestricted_uses:\n- summary: Illegal activity or financial pyramid schemes\n  text: The Customer will not use the Platform for illegal/unlawful actions;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/signifyapp/eligibility/signifyapp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Signify's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Contract Management
- Digital Signature
- Enterprise Software
- Software-as-a-Service
---
