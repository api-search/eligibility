---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Popsa can be delivered throughout the world to you, your family, or friends.
  entity_types:
  - text: You must be at least 18 years old and must be able to enter into legally binding contracts.
    type: individual
  - text: These Terms do not permit use for business purposes.
    type: business
  minimum_age:
    text: You must be at least 18 years old and must be able to enter into legally binding contracts.
    value: '18'
  restricted_uses:
  - summary: Domestic and private use only
    text: We only supply the App for domestic and private use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to purchase Services from Popsa, you must register an account ("Account") using the App.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Popsa
provenance_date: '2026-11-10'
provider_name: Popsa
provider_slug: popsa
slug: popsa-eligibility
source_date: '2026-11-10'
source_filename: popsa-eligibility.yml
source_heading: Eligibility
source_page: https://popsa.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Popsa\naid: popsa\nurl: https://popsa.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Popsa can be delivered throughout the world to you, your family, or friends.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and must be able to enter into legally binding contracts.\n- type: business\n  text: These Terms do not permit use for business purposes.\nrestricted_uses:\n- summary: Domestic and private use only\n  text: We only supply the App for domestic and private use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ In order to purchase Services from Popsa, you must register an account (\"Account\") using the App.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and must be able to enter into legally binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/popsa/eligibility/popsa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Popsa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Photo Printing
- Consumer
- Photo Books
- E-Commerce
- Artificial Intelligence
- Mobile
- B Corporation
---
