---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age (or the age of majority in your jurisdiction) to create an Account and use the Services.
    type: individual
  - text: If you are accessing or using the Services on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age (or the age of majority in your jurisdiction) to create an Account and use the Services.
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
name: Katalyze
provenance_date: '2026-11-09'
provider_name: Katalyze
provider_slug: katalyze
slug: katalyze-eligibility
source_date: '2026-11-09'
source_filename: katalyze-eligibility.yml
source_heading: Eligibility
source_page: https://www.katalyzeai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Katalyze\naid: katalyze\nurl: https://www.katalyzeai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction) to create an Account\n    and use the Services.\n- type: business\n  text: If you are accessing or using the Services on behalf of an organization, you represent and warrant that\n    you have the authority to bind that organization to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction) to create an Account\n    and use the Services.\n"
source_yaml_url: https://artifacts.apis.io/katalyze/eligibility/katalyze-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Katalyze's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Life Sciences
- GxP
- Deviation Investigation
- Yield Optimization
- Raw Material Characterization
- Tech Transfer
- Document Intelligence
---
