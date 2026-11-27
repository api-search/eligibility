---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Service is unauthorized in any jurisdiction where the Service or any part of it may violate any laws or regulations.
  entity_types:
  - text: The Service is intended solely for persons who are 13 years of age or older.
    type: individual
  - text: 'If you’re a business user or an entity: To the extent allowed by applicable law, you’ll indemnify us for any third-party legal proceedings'
    type: business
  minimum_age:
    text: The Service is intended solely for persons who are 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: Cheating on exams or homework
    text: Using it for cheating on exams or homework will primarily hurt you
  - summary: Prohibited user content
    text: You may not submit to the Service any defamatory, inaccurate, abusive, obscene, profane, offensive, sexually oriented, threatening, harassing, racially offensive, or illegal User Content
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
name: Photomath
provenance_date: '2026-11-10'
provider_name: Photomath
provider_slug: photomath
slug: photomath-eligibility
source_date: '2026-11-10'
source_filename: photomath-eligibility.yml
source_heading: Eligibility
source_page: https://photomath.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Photomath\naid: photomath\nurl: https://photomath.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Service is unauthorized in any jurisdiction where the Service or any part of it may violate any\n    laws or regulations.\nentity_types:\n- type: individual\n  text: The Service is intended solely for persons who are 13 years of age or older.\n- type: business\n  text: 'If you’re a business user or an entity: To the extent allowed by applicable law, you’ll indemnify us for\n    any third-party legal proceedings'\nrestricted_uses:\n- summary: Cheating on exams or\
  \ homework\n  text: Using it for cheating on exams or homework will primarily hurt you\n- summary: Prohibited user content\n  text: You may not submit to the Service any defamatory, inaccurate, abusive, obscene, profane, offensive, sexually\n    oriented, threatening, harassing, racially offensive, or illegal User Content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is intended solely for persons who are 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/photomath/eligibility/photomath-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Photomath's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Mathematics
- Learning
- Computer Vision
- Mobile App
- Consumer
- Google
---
