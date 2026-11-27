---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Export control compliance
    text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Company, or any products utilizing such data, in violation of the United States export laws or regulations.
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
name: Plus
provenance_date: '2026-11-10'
provider_name: Plus
provider_slug: plus
slug: plus-eligibility
source_date: '2026-11-10'
source_filename: plus-eligibility.yml
source_heading: Eligibility
source_page: https://www.plus.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plus\naid: plus\nurl: https://www.plus.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control compliance\n  text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired\n    from Company, or any products utilizing such data, in violation of the United States export laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms\
  \ if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/plus/eligibility/plus-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Plus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Autonomous Vehicles
- Self-Driving Trucks
- Autonomous Driving
- Physical AI
- Trucking
- Transportation
- Artificial Intelligence
---
