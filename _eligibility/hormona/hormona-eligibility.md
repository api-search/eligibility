---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We offer our products and services to individuals acting as consumers (as defined under applicable local law).
    type: individual
  - text: Our Products and Services are for domestic and private use.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to accept these Terms and use our products and services
    value: '18'
  restricted_uses:
  - summary: Wellness Tests unsuitable groups
    text: The Hormona Wellness Tests are not suitable for women not of reproductive age
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
name: Hormona
provenance_date: '2026-11-09'
provider_name: Hormona
provider_slug: hormona
slug: hormona-eligibility
source_date: '2026-11-09'
source_filename: hormona-eligibility.yml
source_heading: Eligibility
source_page: https://www.hormona.io/en-us/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hormona\naid: hormona\nurl: https://www.hormona.io/en-us/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: We offer our products and services to individuals acting as consumers (as defined under applicable local\n    law).\n- type: business\n  text: Our Products and Services are for domestic and private use.\nrestricted_uses:\n- summary: Wellness Tests unsuitable groups\n  text: The Hormona Wellness Tests are not suitable for women not of reproductive age\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to accept these Terms and use our products and services\n"
source_yaml_url: https://artifacts.apis.io/hormona/eligibility/hormona-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hormona's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Femtech
- Women's Health
- Hormones
- Wellness
- Consumer Health
- Mobile App
- Sweden
---
