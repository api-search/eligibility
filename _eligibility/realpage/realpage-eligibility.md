---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Realpage SMS alerts are available to users based in the United States. You understand and acknowledge that SMS alerts are not intended to be accessed from outside of the United States.
  entity_types:
  - text: if you are accessing or using the Website on behalf of an entity, you are authorized to accept these Terms on behalf of that entity
    type: business
  minimum_age:
    text: you represent and warrant that (a) you are at least 18 years old and are lawfully able to accept these Terms
    value: '18'
  restricted_uses:
  - summary: Interactive areas personal use only
    text: The Interactive Areas are provided for your personal use.
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
name: RealPage
provenance_date: '2026-11-10'
provider_name: RealPage
provider_slug: realpage
slug: realpage-eligibility
source_date: '2026-11-10'
source_filename: realpage-eligibility.yml
source_heading: Eligibility
source_page: https://www.realpage.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RealPage\naid: realpage\nurl: https://www.realpage.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Realpage SMS alerts are available to users based in the United States. You understand and acknowledge that\n    SMS alerts are not intended to be accessed from outside of the United States.\nentity_types:\n- type: business\n  text: if you are accessing or using the Website on behalf of an entity, you are authorized to accept these Terms\n    on behalf of that entity\nrestricted_uses:\n- summary: Interactive areas personal use only\n  text: The Interactive\
  \ Areas are provided for your personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that (a) you are at least 18 years old and are lawfully able to accept these Terms\n"
source_yaml_url: https://artifacts.apis.io/realpage/eligibility/realpage-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from RealPage's own page on 2026-11-10.
synthetic: false
tags:
- Property Management
- Multifamily
- Rental Housing
- Revenue Management
- Leasing
- PropTech
- Resident Experience
---
