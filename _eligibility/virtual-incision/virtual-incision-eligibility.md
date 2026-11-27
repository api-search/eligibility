---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no claims that the materials are appropriate or may be downloaded outside of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not medical advice
    text: The Company Website is not intended to be used as medical advice, diagnosis, or treatment of any medical condition or health problem
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
name: Virtual Incision
provenance_date: '2026-11-10'
provider_name: Virtual Incision
provider_slug: virtual-incision
slug: virtual-incision-eligibility
source_date: '2026-11-10'
source_filename: virtual-incision-eligibility.yml
source_heading: Eligibility
source_page: https://virtualincision.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Virtual Incision\naid: virtual-incision\nurl: https://virtualincision.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no claims that the materials are appropriate or may be downloaded outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Not medical advice\n  text: The Company Website is not intended to be used as medical advice, diagnosis, or treatment of any medical\n    condition or health problem\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/virtual-incision/eligibility/virtual-incision-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Virtual Incision's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Surgical Robotics
- Robotics
- Healthcare
- Health
- Life Sciences
- Medical Technology
- News
- Careers
- Event
- MCP
---
