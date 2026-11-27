---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Apps, Site and Services are available only to individuals who (a) are at least eighteen (18) years old
    type: individual
  minimum_age:
    text: are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: No medical advice
    text: The App does not provide medical advice, diagnosis, or treatment.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve our right to refuse provision of the Services to anyone, for any reason or for no reason, all subject to applicable law.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Empathy
provenance_date: '2026-11-09'
provider_name: Empathy
provider_slug: empathy
slug: empathy-eligibility
source_date: '2026-11-09'
source_filename: empathy-eligibility.yml
source_heading: Eligibility
source_page: https://www.empathy.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Empathy\naid: empathy\nurl: https://www.empathy.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our Apps, Site and Services are available only to individuals who (a) are at least eighteen (18) years old\nrestricted_uses:\n- summary: No medical advice\n  text: The App does not provide medical advice, diagnosis, or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve our right to refuse provision of the Services to anyone, for any reason or for no reason,\
  \ all\n    subject to applicable law.\nminimum_age:\n  value: '18'\n  text: are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/empathy/eligibility/empathy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Empathy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Estate Planning
- Grief Support
- Insurance
- Wealth Management
- Employee Benefits
- Bereavement
- Financial Services
---
