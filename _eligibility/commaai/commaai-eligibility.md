---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: openpilot is compatible only within the geographical boundaries of the United States of America.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safe, legal use required
    text: it is your responsibility to obey all laws, traffic rules, and traffic regulations governing your vehicle and its operation.
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
name: Comma.ai
provenance_date: '2026-11-09'
provider_name: Comma.ai
provider_slug: commaai
slug: commaai-eligibility
source_date: '2026-11-09'
source_filename: commaai-eligibility.yml
source_heading: Eligibility
source_page: https://comma.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comma.ai\naid: commaai\nurl: https://comma.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: openpilot is compatible only within the geographical boundaries of the United States of America.\nentity_types: []\nrestricted_uses:\n- summary: Safe, legal use required\n  text: it is your responsibility to obey all laws, traffic rules, and traffic regulations governing your vehicle\n    and its operation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/commaai/eligibility/commaai-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Comma.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Self-Driving
- Robotics
- Artificial Intelligence
- Machine Learning
- Open Source
- Connected Vehicles
- Telematics
- Developer API
---
