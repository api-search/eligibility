---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent and warrant that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No commercial purpose
    text: (a) use the Service or any Content for any commercial purpose
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
name: Centific
provenance_date: '2026-11-09'
provider_name: Centific
provider_slug: centific
slug: centific-eligibility
source_date: '2026-11-09'
source_filename: centific-eligibility.yml
source_heading: Eligibility
source_page: https://www.centific.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Centific\naid: centific\nurl: https://www.centific.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No commercial purpose\n  text: (a) use the Service or any Content for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/centific/eligibility/centific-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Centific's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Data Marketplace
- Enterprise AI
- Machine Learning
- Company
---
