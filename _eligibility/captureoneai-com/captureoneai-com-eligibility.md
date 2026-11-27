---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful, harmful or privacy-violating content
    text: Process or distribute illegal, harmful, defamatory, obscene, or privacy-violating content.
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
name: CaptureOneAI
provenance_date: '2026-11-09'
provider_name: CaptureOneAI
provider_slug: captureoneai-com
slug: captureoneai-com-eligibility
source_date: '2026-11-09'
source_filename: captureoneai-com-eligibility.yml
source_heading: Eligibility
source_page: https://captureoneai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CaptureOneAI\naid: captureoneai-com\nurl: https://captureoneai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Unlawful, harmful or privacy-violating content\n  text: Process or distribute illegal, harmful, defamatory, obscene, or privacy-violating content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/captureoneai-com/eligibility/captureoneai-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CaptureOneAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Website Monitoring
- Change Detection
- Screenshots
- PDF Generation
- Web Capture
- Artificial Intelligence
- Alerts
---
