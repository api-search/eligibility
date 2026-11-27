---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Neither you, nor your Accommodation (if you are a Provider) are located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a "terrorist supporting" country
  entity_types:
  - text: If you are entering into these Terms in connection with your employment or on behalf of an organization or entity, you represent to us that you are authorized to bind your employer or such organization or entity
    type: business
  minimum_age:
    text: Use of our Services is limited to users 18 years of age and older and who can form legally binding contracts.
    value: '18'
  restricted_uses:
  - summary: Commercial or business purposes
    text: except as expressly permitted herein, use our Services for commercial or business purposes, including to construct any kind of database or search engine
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
name: Roomi
provenance_date: '2026-11-10'
provider_name: Roomi
provider_slug: roomi
slug: roomi-eligibility
source_date: '2026-11-10'
source_filename: roomi-eligibility.yml
source_heading: Eligibility
source_page: https://roomiapp.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roomi\naid: roomi\nurl: https://roomiapp.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Neither you, nor your Accommodation (if you are a Provider) are located in a country that is subject to\n    a U.S. Government embargo, or that has been designated by the U.S. Government as a \"terrorist supporting\" country\nentity_types:\n- type: business\n  text: If you are entering into these Terms in connection with your employment or on behalf of an organization\n    or entity, you represent to us that you are authorized to bind your employer or such organization or entity\nrestricted_uses:\n\
  - summary: Commercial or business purposes\n  text: except as expressly permitted herein, use our Services for commercial or business purposes, including to\n    construct any kind of database or search engine\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Use of our Services is limited to users 18 years of age and older and who can form legally binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/roomi/eligibility/roomi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Roomi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Real Estate
- Rentals
- Roommates
- Marketplace
- Mobile
---
