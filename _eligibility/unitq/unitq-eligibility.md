---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access the Site from locations other than the United States, you are responsible for compliance
  minimum_age:
    text: if you are a child under 13, please do not attempt to register for the Services or send any personal information about yourself to us.
    value: null
  restricted_uses:
  - summary: No commercial use of materials
    text: you may not use the materials for any commercial purpose.
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
name: unitQ
provenance_date: '2026-11-10'
provider_name: unitQ
provider_slug: unitq
slug: unitq-eligibility
source_date: '2026-11-10'
source_filename: unitq-eligibility.yml
source_heading: Eligibility
source_page: https://www.unitq.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: unitQ\naid: unitq\nurl: https://www.unitq.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access the Site from locations other than the United States, you are responsible for compliance\nentity_types: []\nrestricted_uses:\n- summary: No commercial use of materials\n  text: you may not use the materials for any commercial purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: if you are a child under 13, please do not attempt to register for the Services or send any personal information\n\
  \    about yourself to us.\n"
source_yaml_url: https://artifacts.apis.io/unitq/eligibility/unitq-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from unitQ's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Customer Feedback
- Product Quality
- Feedback Analytics
- Support Experience
- Voice of Customer
---
