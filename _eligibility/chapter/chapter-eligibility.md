---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Chapter, and not otherwise barred from using the Services under applicable law.
    type: individual
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: 'Post, upload, publish, submit or transmit any Submitted Information that: (i) infringes, misappropriates or violates a third party''s patent, copyright, trademark, trade secret, moral rights or other intellectual property rights'
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
name: Chapter
provenance_date: '2026-11-09'
provider_name: Chapter
provider_slug: chapter
slug: chapter-eligibility
source_date: '2026-11-09'
source_filename: chapter-eligibility.yml
source_heading: Eligibility
source_page: https://askchapter.org/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chapter\naid: chapter\nurl: https://askchapter.org/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Chapter, and not otherwise barred from using the Services under applicable law.\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: 'Post, upload, publish, submit or transmit any Submitted Information that: (i) infringes, misappropriates\n    or violates a third party''s patent, copyright, trademark,\
  \ trade secret, moral rights or other intellectual\n    property rights'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/chapter/eligibility/chapter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Chapter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Medicare
- Insurance
- Health Insurance
- Senior Care
- Retirement
- Consumer Health
---
