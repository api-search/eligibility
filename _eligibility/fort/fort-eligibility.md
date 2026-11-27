---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Site, you represent that you are at least 18 years of age, have the legal authority to enter into this agreement, and agree to comply with these Terms.
    type: individual
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Prohibited referral activities
    text: Self-referrals (referring yourself using multiple accounts or identities).
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
name: Fort
provenance_date: '2026-11-09'
provider_name: Fort
provider_slug: fort
slug: fort-eligibility
source_date: '2026-11-09'
source_filename: fort-eligibility.yml
source_heading: Eligibility
source_page: https://fort.cx/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fort\naid: fort\nurl: https://fort.cx/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Site, you represent that you are at least 18 years of age, have the legal authority to enter\n    into this agreement, and agree to comply with these Terms.\nrestricted_uses:\n- summary: Prohibited referral activities\n  text: Self-referrals (referring yourself using multiple accounts or identities).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/fort/eligibility/fort-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fort's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wearables
- Health
- Fitness
- Strength Training
- Consumer Hardware
- Longevity
- IoT
---
