---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not access or use any Website or accept the Terms if you are not at least 18 years old.
    type: individual
  minimum_age:
    text: You may not access or use any Website or accept the Terms if you are not at least 18 years old.
    value: '18'
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
name: Curebase
provenance_date: '2026-11-09'
provider_name: Curebase
provider_slug: curebase
slug: curebase-eligibility
source_date: '2026-11-09'
source_filename: curebase-eligibility.yml
source_heading: Eligibility
source_page: https://www.curebase.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curebase\naid: curebase\nurl: https://www.curebase.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not access or use any Website or accept the Terms if you are not at least 18 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use any Website or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/curebase/eligibility/curebase-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Curebase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Clinical Trials
- eClinical
- Life Sciences
- Healthcare
- Decentralized Clinical Trials
- Electronic Data Capture
- Patient Engagement
---
