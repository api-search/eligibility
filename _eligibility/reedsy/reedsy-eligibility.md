---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if registering as an individual, be 18 (eighteen) years of age or otherwise capable of entering into legally binding contracts;
    type: individual
  - text: if registering on behalf of a legal entity, have the requisite authority to enter into these Terms of Use on behalf of the entity and ensuring performance of these Terms of Use;
    type: business
  minimum_age:
    text: if registering as an individual, be 18 (eighteen) years of age or otherwise capable of entering into legally binding contracts;
    value: '18'
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
name: Reedsy
provenance_date: '2026-11-10'
provider_name: Reedsy
provider_slug: reedsy
slug: reedsy-eligibility
source_date: '2026-11-10'
source_filename: reedsy-eligibility.yml
source_heading: Eligibility
source_page: https://reedsy.com/about/tou
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reedsy\naid: reedsy\nurl: https://reedsy.com/about/tou\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if registering as an individual, be 18 (eighteen) years of age or otherwise capable of entering into legally\n    binding contracts;\n- type: business\n  text: if registering on behalf of a legal entity, have the requisite authority to enter into these Terms of Use\n    on behalf of the entity and ensuring performance of these Terms of Use;\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: if registering as an individual, be 18 (eighteen) years of age or otherwise capable of entering into legally\n    binding contracts;\n"
source_yaml_url: https://artifacts.apis.io/reedsy/eligibility/reedsy-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Reedsy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Publishing
- Writing
- Marketplace
- Book Publishing
- Authors
- Editing
- Self-Publishing
---
