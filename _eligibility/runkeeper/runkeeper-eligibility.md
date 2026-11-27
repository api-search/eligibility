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
  - summary: Not medical advice
    text: THE SERVICES DO NOT CONTAIN OR CONSTITUTE, AND SHOULD NOT BE INTERPRETED AS, MEDICAL ADVICE OR OPINION
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
name: Runkeeper
provenance_date: '2026-11-10'
provider_name: Runkeeper
provider_slug: runkeeper
slug: runkeeper-eligibility
source_date: '2026-11-10'
source_filename: runkeeper-eligibility.yml
source_heading: Eligibility
source_page: https://runkeeper.com/cms/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Runkeeper\naid: runkeeper\nurl: https://runkeeper.com/cms/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not medical advice\n  text: THE SERVICES DO NOT CONTAIN OR CONSTITUTE, AND SHOULD NOT BE INTERPRETED AS, MEDICAL ADVICE OR OPINION\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/runkeeper/eligibility/runkeeper-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Runkeeper's own page on 2026-11-10.
synthetic: false
tags:
- Fitness
- Social
- Mobile App
- Tracking
- Community
- Health
---
