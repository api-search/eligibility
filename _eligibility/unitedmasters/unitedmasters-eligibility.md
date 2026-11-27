---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You cannot access or use the Services from, or transmit the Services into, any jurisdictions prohibited by applicable law.
  entity_types:
  - text: You must be at least 18 years of age to use the Services and otherwise have all legal authority to enter into these Terms.
    type: individual
  - text: have all legal rights and authority to enter into these Terms on behalf of yourself, or any legal entity that you represent.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Services
    value: '18'
  restricted_uses:
  - summary: Export-controlled or sanctioned parties
    text: You also cannot use the Services if you are yourself prohibited by the U.S. government from accessing or using our Services.
  - summary: Commercial use
    text: use the Services for commercial purposes, except as permitted by us or in compliance with an applicable developer agreement or API provided by us
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
name: UnitedMasters
provenance_date: '2026-11-10'
provider_name: UnitedMasters
provider_slug: unitedmasters
slug: unitedmasters-eligibility
source_date: '2026-11-10'
source_filename: unitedmasters-eligibility.yml
source_heading: Eligibility
source_page: https://unitedmasters.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UnitedMasters\naid: unitedmasters\nurl: https://unitedmasters.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You cannot access or use the Services from, or transmit the Services into, any jurisdictions prohibited\n    by applicable law.\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services and otherwise have all legal authority to enter\n    into these Terms.\n- type: business\n  text: have all legal rights and authority to enter into these Terms on behalf of yourself, or any legal entity\n    that you represent.\nrestricted_uses:\n\
  - summary: Export-controlled or sanctioned parties\n  text: You also cannot use the Services if you are yourself prohibited by the U.S. government from accessing or\n    using our Services.\n- summary: Commercial use\n  text: use the Services for commercial purposes, except as permitted by us or in compliance with an applicable\n    developer agreement or API provided by us\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Services\n"
source_yaml_url: https://artifacts.apis.io/unitedmasters/eligibility/unitedmasters-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from UnitedMasters's own page on 2026-11-10.
synthetic: false
tags:
- Music
- Music Distribution
- Streaming
- Royalties
- Creator Economy
- Entertainment
- Media
---
