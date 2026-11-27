---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer user, please note that we only provide our site for domestic and private use.
    type: individual
  - text: 'If you are a business user, please note that in particular, we will not be liable for: loss of profits, sales, business, or revenue; business interruption; loss of anticipated savings; loss of business opportunity, goodwill or reputation; or any indirect or consequential loss or damage.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use by consumer users
    text: You agree not to use our site for any commercial or business purposes
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
name: LabGenius Therapeutics
provenance_date: '2026-11-09'
provider_name: LabGenius Therapeutics
provider_slug: labgenius
slug: labgenius-eligibility
source_date: '2026-11-09'
source_filename: labgenius-eligibility.yml
source_heading: Eligibility
source_page: https://labgeniustx.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LabGenius Therapeutics\naid: labgenius\nurl: https://labgeniustx.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer user, please note that we only provide our site for domestic and private use.\n- type: business\n  text: 'If you are a business user, please note that in particular, we will not be liable for: loss of profits,\n    sales, business, or revenue; business interruption; loss of anticipated savings; loss of business opportunity,\n    goodwill or reputation; or any indirect or consequential\
  \ loss or damage.'\nrestricted_uses:\n- summary: No commercial use by consumer users\n  text: You agree not to use our site for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/labgenius/eligibility/labgenius-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from LabGenius Therapeutics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Drug Discovery
- Therapeutics
- Antibodies
- Machine Learning
- Artificial Intelligence
- Life Sciences
- Oncology
- Laboratory Automation
- Synthetic Biology
---
