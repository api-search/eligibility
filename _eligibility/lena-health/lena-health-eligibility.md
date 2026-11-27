---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Site or interact with the Services on your own behalf.
    type: individual
  - text: Services we provide to healthcare organizations and their partners are governed by separate written agreements, including business associate agreements
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Site or interact with the Services on your own behalf.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: The Services are not for emergencies.
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
name: Lena Health
provenance_date: '2026-11-09'
provider_name: Lena Health
provider_slug: lena-health
slug: lena-health-eligibility
source_date: '2026-11-09'
source_filename: lena-health-eligibility.yml
source_heading: Eligibility
source_page: https://lena.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lena Health\naid: lena-health\nurl: https://lena.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Site or interact with the Services on your own behalf.\n- type: business\n  text: Services we provide to healthcare organizations and their partners are governed by separate written agreements,\n    including business associate agreements\nrestricted_uses:\n- summary: Not for emergencies\n  text: The Services are not for emergencies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Site or interact with the Services on your own behalf.\n"
source_yaml_url: https://artifacts.apis.io/lena-health/eligibility/lena-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lena Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Care Coordination
- Care Navigation
- Artificial Intelligence
- Patient Engagement
- Chronic Care Management
- Health Plans
- Digital Health
- HIPAA
---
