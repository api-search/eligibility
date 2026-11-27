---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you confirm that you are at least 18 years of age, have read and understood these Terms
    type: individual
  - text: If you are accessing the services on behalf of an organisation, you represent that you have authority to bind that organisation.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years of age
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
name: SigTuple
provenance_date: '2026-11-10'
provider_name: SigTuple
provider_slug: sigtuple
slug: sigtuple-eligibility
source_date: '2026-11-10'
source_filename: sigtuple-eligibility.yml
source_heading: Eligibility
source_page: https://sigtuple.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SigTuple\naid: sigtuple\nurl: https://sigtuple.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you confirm that you are at least 18 years of age, have read and understood these Terms\n- type: business\n  text: If you are accessing the services on behalf of an organisation, you represent that you have authority to\n    bind that organisation.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years\
  \ of age\n"
source_yaml_url: https://artifacts.apis.io/sigtuple/eligibility/sigtuple-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from SigTuple's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Healthcare
- Diagnostics
- Pathology
- Medical Devices
- Microscopy
- Machine Learning
---
