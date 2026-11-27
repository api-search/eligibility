---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: User must be at least 18 years and shall have the legal capacity to use, browse or register a User Account on the Platform.
    type: individual
  minimum_age:
    text: the User must be at least 18 years and shall have the legal capacity
    value: '18'
  restricted_uses:
  - summary: No content violating law or public order
    text: Upload, publish and/or share inappropriate content on the Platform or illegal, offensive to human dignity, of a sexual nature, defamatory, abusive, racist or any other content that may give rise to civil or criminal liability
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
name: Onefinestay
provenance_date: '2026-11-10'
provider_name: Onefinestay
provider_slug: onefinestay
slug: onefinestay-eligibility
source_date: '2026-11-10'
source_filename: onefinestay-eligibility.yml
source_heading: Eligibility
source_page: https://www.onefinestay.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Onefinestay\naid: onefinestay\nurl: https://www.onefinestay.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: User must be at least 18 years and shall have the legal capacity to use, browse or register a User Account\n    on the Platform.\nrestricted_uses:\n- summary: No content violating law or public order\n  text: Upload, publish and/or share inappropriate content on the Platform or illegal, offensive to human dignity,\n    of a sexual nature, defamatory, abusive, racist or any other content that may give rise to\
  \ civil or criminal\n    liability\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the User must be at least 18 years and shall have the legal capacity\n"
source_yaml_url: https://artifacts.apis.io/onefinestay/eligibility/onefinestay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Onefinestay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hospitality
- Travel
- Vacation Rentals
- Luxury
- Accommodation
- Real Estate
---
