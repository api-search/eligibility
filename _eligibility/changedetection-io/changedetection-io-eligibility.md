---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years of age or older to use the Services.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful user content
    text: User Content that is unlawful, libelous, defamatory, obscene, pornographic, harassing, threatening
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
name: changedetection.io
provenance_date: '2026-11-09'
provider_name: changedetection.io
provider_slug: changedetection-io
slug: changedetection-io-eligibility
source_date: '2026-11-09'
source_filename: changedetection-io-eligibility.yml
source_heading: Eligibility
source_page: https://changedetection.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: changedetection.io\naid: changedetection-io\nurl: https://changedetection.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to use the Services.\nrestricted_uses:\n- summary: Unlawful or harmful user content\n  text: User Content that is unlawful, libelous, defamatory, obscene, pornographic, harassing, threatening\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the\
  \ Services.\n"
source_yaml_url: https://artifacts.apis.io/changedetection-io/eligibility/changedetection-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from changedetection.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Monitoring
- Webhook
- Alerts
- Open Source
---
