---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is intended for healthcare professionals and institutional purchasers in the United States.
  entity_types:
  - text: The Website is intended for healthcare professionals and institutional purchasers in the United States.
    type: individual
  - text: The Website is intended for healthcare professionals and institutional purchasers in the United States.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No PHI submissions
    text: Do not submit Protected Health Information (PHI) via Website forms, email addresses, or chat unless your institution has an executed Business Associate Agreement (BAA) with Healthleap and we have provided a designated secure channel.
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
name: Healthleap
provenance_date: '2026-11-09'
provider_name: Healthleap
provider_slug: healthleap
slug: healthleap-eligibility
source_date: '2026-11-09'
source_filename: healthleap-eligibility.yml
source_heading: Eligibility
source_page: https://healthleap.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Healthleap\naid: healthleap\nurl: https://healthleap.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is intended for healthcare professionals and institutional purchasers in the United States.\nentity_types:\n- type: individual\n  text: The Website is intended for healthcare professionals and institutional purchasers in the United States.\n- type: business\n  text: The Website is intended for healthcare professionals and institutional purchasers in the United States.\nrestricted_uses:\n- summary: No PHI submissions\n  text: Do not submit Protected Health\
  \ Information (PHI) via Website forms, email addresses, or chat unless your\n    institution has an executed Business Associate Agreement (BAA) with Healthleap and we have provided a designated\n    secure channel.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/healthleap/eligibility/healthleap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Healthleap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Healthcare
- Risk Screening
- Nutrition
---
