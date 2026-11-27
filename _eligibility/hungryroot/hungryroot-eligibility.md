---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To use the Hungryroot Platform and to accept these Terms, you must (1) be a legal resident of the United States
  entity_types:
  - text: Eligibility to participate in the Program is limited to individuals only.
    type: individual
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Referral program personal use only
    text: The Program should only be used for personal and non-commercial purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: In order to use certain Services, Hungryroot may be required to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hungryroot
provenance_date: '2026-11-09'
provider_name: Hungryroot
provider_slug: hungryroot
slug: hungryroot-eligibility
source_date: '2026-11-09'
source_filename: hungryroot-eligibility.yml
source_heading: Eligibility
source_page: https://www.hungryroot.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hungryroot\naid: hungryroot\nurl: https://www.hungryroot.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To use the Hungryroot Platform and to accept these Terms, you must (1) be a legal resident of the United\n    States\nentity_types:\n- type: individual\n  text: Eligibility to participate in the Program is limited to individuals only.\nrestricted_uses:\n- summary: Referral program personal use only\n  text: The Program should only be used for personal and non-commercial purposes.\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: In order to use certain Services, Hungryroot may be required to verify your identity.\nminimum_age:\n  value: '18'\n  text: be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/hungryroot/eligibility/hungryroot-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Hungryroot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Grocery
- Meal Kit
- Food Delivery
- Direct to Consumer
- Personalization
- E-Commerce
- Consumer
---
