---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: YOU ARE NOT LOCATED IN A COUNTRY THAT IS SUBJECT TO A U.S. GOVERNMENT EMBARGO
  entity_types:
  - text: You may not access or use the App or accept the Terms if you are not at least 18 years old.
    type: individual
  - text: you represent and warrant that you have the right, authority, and capacity to enter into these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: You may not access or use the App or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: use the App for any illegal, unauthorized, unintended, unsafe, hazardous, fraudulent, deceptive or unlawful purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must register for an account (“ Account ”) and provide certain information about yourself as prompted by the account registration form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MaxRewards
provenance_date: '2026-11-10'
provider_name: MaxRewards
provider_slug: maxrewards
slug: maxrewards-eligibility
source_date: '2026-11-10'
source_filename: maxrewards-eligibility.yml
source_heading: Eligibility
source_page: https://maxrewards.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MaxRewards\naid: maxrewards\nurl: https://maxrewards.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: YOU ARE NOT LOCATED IN A COUNTRY THAT IS SUBJECT TO A U.S. GOVERNMENT EMBARGO\nentity_types:\n- type: individual\n  text: You may not access or use the App or accept the Terms if you are not at least 18 years old.\n- type: business\n  text: you represent and warrant that you have the right, authority, and capacity to enter into these Terms (on\n    behalf of yourself or the entity that you represent)\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text:\
  \ use the App for any illegal, unauthorized, unintended, unsafe, hazardous, fraudulent, deceptive or unlawful\n    purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must register for an account (“ Account ”) and provide certain information about yourself as prompted\n    by the account registration form.\nminimum_age:\n  value: '18'\n  text: You may not access or use the App or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/maxrewards/eligibility/maxrewards-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from MaxRewards's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Credit Cards
- Rewards
- Personal Finance
- Consumer App
- Cashback
- Techstars
---
