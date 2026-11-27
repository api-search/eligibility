---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and legally allowed to use put.io.
    type: individual
  minimum_age:
    text: You must be at least 18 and legally allowed to use put.io.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: Don't use put.io to break the law or infringe on other people's rights.
  - summary: Malware or ransomware
    text: Don't create, host or distribute malware, or run ransomware attacks.
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
name: put.io
provenance_date: '2026-11-10'
provider_name: put.io
provider_slug: put-io
slug: put-io-eligibility
source_date: '2026-11-10'
source_filename: put-io-eligibility.yml
source_heading: Eligibility
source_page: https://put.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: put.io\naid: put-io\nurl: https://put.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally allowed to use put.io.\nrestricted_uses:\n- summary: Unlawful use\n  text: Don't use put.io to break the law or infringe on other people's rights.\n- summary: Malware or ransomware\n  text: Don't create, host or distribute malware, or run ransomware attacks.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 and legally allowed to use put.io.\n"
source_yaml_url: https://artifacts.apis.io/put-io/eligibility/put-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from put.io's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Storage
- Media Streaming
- File Management
- Automation
---
