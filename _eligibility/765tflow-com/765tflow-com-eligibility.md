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
  - summary: Account sharing outside organisation
    text: share your account outside your organisation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: An account and a sign-in from 765T Flow Control Center are the intended steps before FLOW runs.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 765T Flow
provenance_date: '2026-11-09'
provider_name: 765T Flow
provider_slug: 765tflow-com
slug: 765tflow-com-eligibility
source_date: '2026-11-09'
source_filename: 765tflow-com-eligibility.yml
source_heading: Eligibility
source_page: https://765tflow.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 765T Flow\naid: 765tflow-com\nurl: https://765tflow.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Account sharing outside organisation\n  text: share your account outside your organisation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: An account and a sign-in from 765T Flow Control Center are the intended steps before FLOW runs.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/765tflow-com/eligibility/765tflow-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from 765T Flow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Revit
- BIM
- Automation
---
