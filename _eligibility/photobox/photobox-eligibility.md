---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You guarantee that the orders you place are for private and non-commercial use and that you are acting as a consumer.
    type: individual
  minimum_age:
    text: If you are under sixteen (16) years of age, you need permission from your parents or legal guardians for requesting an online version of your photo book.
    value: '16'
  restricted_uses:
  - summary: Private, non-commercial use only
    text: You guarantee that the orders you place are for private and non-commercial use and that you are acting as a consumer.
  - summary: No illicit photo content
    text: You also guarantee that the photos uploaded to our services through your account are not in breach of criminal law, statutory provisions of mandatory civil, administrative or other applicable law, public order, public morality or what is, according to unwritten law, to be regarded as proper social conduct.
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
name: Photobox
provenance_date: '2026-11-10'
provider_name: Photobox
provider_slug: photobox
slug: photobox-eligibility
source_date: '2026-11-10'
source_filename: photobox-eligibility.yml
source_heading: Eligibility
source_page: https://www.photobox.co.uk/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Photobox\naid: photobox\nurl: https://www.photobox.co.uk/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You guarantee that the orders you place are for private and non-commercial use and that you are acting as\n    a consumer.\nrestricted_uses:\n- summary: Private, non-commercial use only\n  text: You guarantee that the orders you place are for private and non-commercial use and that you are acting as\n    a consumer.\n- summary: No illicit photo content\n  text: You also guarantee that the photos uploaded to our\
  \ services through your account are not in breach of criminal\n    law, statutory provisions of mandatory civil, administrative or other applicable law, public order, public morality\n    or what is, according to unwritten law, to be regarded as proper social conduct.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: If you are under sixteen (16) years of age, you need permission from your parents or legal guardians for\n    requesting an online version of your photo book.\n"
source_yaml_url: https://artifacts.apis.io/photobox/eligibility/photobox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Photobox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Photo Printing
- Personalised Gifts
- E-Commerce
- Photo Books
- Retail
- Europe
---
