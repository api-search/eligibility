---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are offered and available only to users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
  entity_types:
  - text: The Services are offered and available only to users who are 18 years of age or older and reside in the United States or any of its territories or possessions.
    type: individual
  - text: If you are accessing or using the Services on behalf of an entity, you represent that you have the authority to bind the entity to these Terms.
    type: business
  minimum_age:
    text: The Services are offered and available only to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No emergency or crisis use
    text: The AI Features cannot respond to emergency or crisis situations. Do not use the Services, including the AI Features, for urgent or life-threatening issues.
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
name: Nourish
provenance_date: '2026-11-10'
provider_name: Nourish
provider_slug: nourish
slug: nourish-eligibility
source_date: '2026-11-10'
source_filename: nourish-eligibility.yml
source_heading: Eligibility
source_page: https://www.nourish.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nourish\naid: nourish\nurl: https://www.nourish.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are offered and available only to users who are 18 years of age or older and reside in the\n    United States or any of its territories or possessions.\nentity_types:\n- type: individual\n  text: The Services are offered and available only to users who are 18 years of age or older and reside in the\n    United States or any of its territories or possessions.\n- type: business\n  text: If you are accessing or using the Services on behalf of an entity, you represent\
  \ that you have the authority\n    to bind the entity to these Terms.\nrestricted_uses:\n- summary: No emergency or crisis use\n  text: The AI Features cannot respond to emergency or crisis situations. Do not use the Services, including the\n    AI Features, for urgent or life-threatening issues.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are offered and available only to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/nourish/eligibility/nourish-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Nourish's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Nutrition
- Dietitian
- Telehealth
- Digital Health
- Insurance
- Wellness
---
