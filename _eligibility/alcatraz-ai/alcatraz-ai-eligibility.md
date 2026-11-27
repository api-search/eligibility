---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Biometric enrollment requires consent
    text: Enrollment on an Alcatraz device is governed by the Solution Owner and cannot begin without recorded consent
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
name: Alcatraz AI
provenance_date: '2026-11-09'
provider_name: Alcatraz AI
provider_slug: alcatraz-ai
slug: alcatraz-ai-eligibility
source_date: '2026-11-09'
source_filename: alcatraz-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.alcatraz.ai/utilities/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alcatraz AI\naid: alcatraz-ai\nurl: https://www.alcatraz.ai/utilities/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Biometric enrollment requires consent\n  text: Enrollment on an Alcatraz device is governed by the Solution Owner and cannot begin without recorded consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alcatraz-ai/eligibility/alcatraz-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Alcatraz AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Access Control
- Biometrics
- Facial Authentication
- Physical Security
- Identity
- IoT
- Artificial Intelligence
---
