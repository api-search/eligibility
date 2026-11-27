---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old or have reached the age of majority in your jurisdiction to use our Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old or have reached the age of majority in your jurisdiction to use our Service.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Certain features require account creation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bonfire Analytics
provenance_date: '2026-11-09'
provider_name: Bonfire Analytics
provider_slug: bonfire-analytics
slug: bonfire-analytics-eligibility
source_date: '2026-11-09'
source_filename: bonfire-analytics-eligibility.yml
source_heading: Eligibility
source_page: https://www.bonfireanalytics.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bonfire Analytics\naid: bonfire-analytics\nurl: https://www.bonfireanalytics.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or have reached the age of majority in your jurisdiction to use our Service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Certain features require account creation.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or have reached the age of majority in your jurisdiction to use our\
  \ Service.\n"
source_yaml_url: https://artifacts.apis.io/bonfire-analytics/eligibility/bonfire-analytics-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Bonfire Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Sales Intelligence
- B2B
- Data Analytics
- Company
---
