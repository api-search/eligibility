---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use of and participation on the System is restricted to those individuals who are at least 18 years of age and are fully able and competent to enter into the terms
    type: individual
  minimum_age:
    text: Use of and participation on the System is restricted to those individuals who are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Harmful interference and unlawful transmissions
    text: transmit any unlawful, threatening, abusive, libelous, defamatory, obscene, vulgar, pornographic, profane or indecent information of any kind, including images and language
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
name: Comscore
provenance_date: '2026-11-09'
provider_name: Comscore
provider_slug: comscore
slug: comscore-eligibility
source_date: '2026-11-09'
source_filename: comscore-eligibility.yml
source_heading: Eligibility
source_page: https://www.comscore.com/About/Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comscore\naid: comscore\nurl: https://www.comscore.com/About/Terms-of-Service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use of and participation on the System is restricted to those individuals who are at least 18 years of age\n    and are fully able and competent to enter into the terms\nrestricted_uses:\n- summary: Harmful interference and unlawful transmissions\n  text: transmit any unlawful, threatening, abusive, libelous, defamatory, obscene, vulgar, pornographic, profane\n    or indecent information of any kind, including\
  \ images and language\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Use of and participation on the System is restricted to those individuals who are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/comscore/eligibility/comscore-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Comscore's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Saas
- Media Measurement
- Audience Analytics
- Advertising
- Programmatic
- Streaming
- Cross-Platform Measurement
---
