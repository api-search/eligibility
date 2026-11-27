---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Viome Pro Solutions are available only in the US; Subscription Services are currently available in the United States from our website.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for diagnosis
    text: Such Health and Wellness Insights and outputs are not intended to diagnose, treat, cure, mitigate, monitor, or prevent any disease or medical condition
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
name: Viome
provenance_date: '2026-11-10'
provider_name: Viome
provider_slug: viome
slug: viome-eligibility
source_date: '2026-11-10'
source_filename: viome-eligibility.yml
source_heading: Eligibility
source_page: https://www.viome.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Viome\naid: viome\nurl: https://www.viome.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Viome Pro Solutions are available only in the US; Subscription Services are currently available in the United\n    States from our website.\nentity_types: []\nrestricted_uses:\n- summary: Not for diagnosis\n  text: Such Health and Wellness Insights and outputs are not intended to diagnose, treat, cure, mitigate, monitor,\n    or prevent any disease or medical condition\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/viome/eligibility/viome-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Viome's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Microbiome
- Genomics
- Diagnostics
- Nutrition
- Life Sciences
- Artificial Intelligence
- Consumer Health
---
