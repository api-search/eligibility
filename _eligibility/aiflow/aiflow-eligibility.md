---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is not intended for use in any jurisdiction where such use would be illegal or require registration.
  minimum_age:
    text: Users must be at least 18 years old to use or register for the Site.
    value: '18'
  restricted_uses:
  - summary: Regulated interactions (HIPAA, FISMA, GLBA)
    text: The Site does not comply with industry-specific regulations (e.g., HIPAA, FISMA, GLBA). Do not use if your interactions are subject to these regulations.
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
name: aiFlow
provenance_date: '2026-11-09'
provider_name: aiFlow
provider_slug: aiflow
slug: aiflow-eligibility
source_date: '2026-11-09'
source_filename: aiflow-eligibility.yml
source_heading: Eligibility
source_page: https://www.veratainsight.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: aiFlow\naid: aiflow\nurl: https://www.veratainsight.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is not intended for use in any jurisdiction where such use would be illegal or require registration.\nentity_types: []\nrestricted_uses:\n- summary: Regulated interactions (HIPAA, FISMA, GLBA)\n  text: The Site does not comply with industry-specific regulations (e.g., HIPAA, FISMA, GLBA). Do not use if your\n    interactions are subject to these regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: Users must be at least 18 years old to use or register for the Site.\n"
source_yaml_url: https://artifacts.apis.io/aiflow/eligibility/aiflow-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from aiFlow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Executive Search
- Private Equity
- Talent Intelligence
- People Data
- Company Data
- Market Intelligence
- Artificial Intelligence
- Y Combinator
---
