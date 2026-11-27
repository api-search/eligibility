---
claim_count: 2
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
  - summary: Sanctions restriction for applications
    text: You are not located in a country that is subject to any Government sanctions, and you are not listed on any Government list of prohibited or restricted parties
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: We do not verify any of the information you provide in an Application including, but not limited to, the verification of your identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BridgeU
provenance_date: '2026-11-09'
provider_name: BridgeU
provider_slug: bridgeu
slug: bridgeu-eligibility
source_date: '2026-11-09'
source_filename: bridgeu-eligibility.yml
source_heading: Eligibility
source_page: https://bridge-u.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BridgeU\naid: bridgeu\nurl: https://bridge-u.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctions restriction for applications\n  text: You are not located in a country that is subject to any Government sanctions, and you are not listed on\n    any Government list of prohibited or restricted parties\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: We do not verify any of the information you provide in an Application including, but not limited to, the\n    verification of your identity\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bridgeu/eligibility/bridgeu-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from BridgeU's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- University Guidance
- Careers Guidance
- Student Success
- International Schools
- Software-as-a-Service
---
