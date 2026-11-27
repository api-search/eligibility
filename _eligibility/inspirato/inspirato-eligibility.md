---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 21 years of age and possess the legal authority to create a binding obligation
    type: individual
  minimum_age:
    text: you are at least 21 years of age
    value: '21'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Travel is subject to acceptance of terms and conditions and other eligibility requirements.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Inspirato
provenance_date: '2026-11-09'
provider_name: Inspirato
provider_slug: inspirato
slug: inspirato-eligibility
source_date: '2026-11-09'
source_filename: inspirato-eligibility.yml
source_heading: Eligibility
source_page: https://www.inspirato.com/legal-pages/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inspirato\naid: inspirato\nurl: https://www.inspirato.com/legal-pages/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 21 years of age and possess the legal authority to create a binding obligation\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Travel is subject to acceptance of terms and conditions and other eligibility requirements.\nminimum_age:\n  value: '21'\n  text: you are at least 21 years of age\n"
source_yaml_url: https://artifacts.apis.io/inspirato/eligibility/inspirato-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Inspirato's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Hospitality
- Luxury
- Subscription
- Membership
- Concierge
---
