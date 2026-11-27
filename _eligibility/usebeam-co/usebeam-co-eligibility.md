---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: you agree to provide Beam accurate and complete information about you and your business
    type: business
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: not stated
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: you will not use the Site for any illegal or unauthorized purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As a condition of Beam enabling payment processing services through Stripe, you agree to provide Beam accurate and complete information about you and your business
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beam
provenance_date: '2026-11-10'
provider_name: Beam
provider_slug: usebeam-co
slug: usebeam-co-eligibility
source_date: '2026-11-10'
source_filename: usebeam-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.trybeam.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beam\naid: usebeam-co\nurl: https://www.trybeam.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: business\n  text: you agree to provide Beam accurate and complete information about you and your business\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: you will not use the Site for any illegal or unauthorized purpose\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As a condition of Beam enabling payment processing services through Stripe, you agree to provide Beam accurate\n    and complete information about you and your business\nminimum_age:\n  value: not stated\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/usebeam-co/eligibility/usebeam-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Beam's own page on 2026-11-10.
synthetic: false
tags:
- Construction
- Finance
- Software
- Project Management
- Software-as-a-Service
---
