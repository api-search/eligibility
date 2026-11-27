---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To access or use the Site, you must be 18 years or older and have the requisite power and authority to enter into these Terms of Service.
    type: individual
  minimum_age:
    text: To access or use the Site, you must be 18 years or older and have the requisite power and authority to enter into these Terms of Service.
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
name: Bindo
provenance_date: '2026-11-09'
provider_name: Bindo
provider_slug: bindo
slug: bindo-eligibility
source_date: '2026-11-09'
source_filename: bindo-eligibility.yml
source_heading: Eligibility
source_page: https://bindolabs.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bindo\naid: bindo\nurl: https://bindolabs.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To access or use the Site, you must be 18 years or older and have the requisite power and authority to enter\n    into these Terms of Service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To access or use the Site, you must be 18 years or older and have the requisite power and authority to enter\n    into these Terms of Service.\n"
source_yaml_url: https://artifacts.apis.io/bindo/eligibility/bindo-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Bindo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Point-of-Sale
- Retail
- Hospitality
- Payments
---
