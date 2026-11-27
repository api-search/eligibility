---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are 18 years of age or older, are lawfully able to enter into contracts and agree to be bound by these Terms of Service.
    type: individual
  minimum_age:
    text: You represent that you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No unlawful or harmful content
    text: 'You may not use the Services to: (a) Upload, post, e-mail or otherwise transmit any content that is unlawful, harmful, threatening, intimidating, abusive, harassing'
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
name: SchoolCare
provenance_date: '2026-11-09'
provider_name: SchoolCare
provider_slug: caredox
slug: caredox-eligibility
source_date: '2026-11-09'
source_filename: caredox-eligibility.yml
source_heading: Eligibility
source_page: https://schoolcare.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SchoolCare\naid: caredox\nurl: https://schoolcare.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are 18 years of age or older, are lawfully able to enter into contracts and agree\n    to be bound by these Terms of Service.\nrestricted_uses:\n- summary: No unlawful or harmful content\n  text: 'You may not use the Services to: (a) Upload, post, e-mail or otherwise transmit any content that is unlawful,\n    harmful, threatening, intimidating, abusive, harassing'\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/caredox/eligibility/caredox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SchoolCare's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Health
- Software-as-a-Service
- K-12
- Student Records
---
