---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using Careforce, you confirm that you are of legal age and meet all eligibility requirements under applicable laws and regulations.
    value: null
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
name: Careforce
provenance_date: '2026-11-09'
provider_name: Careforce
provider_slug: careforce
slug: careforce-eligibility
source_date: '2026-11-09'
source_filename: careforce-eligibility.yml
source_heading: Eligibility
source_page: https://careforce.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Careforce\naid: careforce\nurl: https://careforce.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By using Careforce, you confirm that you are of legal age and meet all eligibility requirements under applicable\n    laws and regulations.\n"
source_yaml_url: https://artifacts.apis.io/careforce/eligibility/careforce-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Careforce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Agents
- Care Coordination
- Automation
- EHR Integration
- Patient Outreach
---
