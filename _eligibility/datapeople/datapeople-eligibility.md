---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
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
name: DataPeople
provenance_date: '2026-11-09'
provider_name: DataPeople
provider_slug: datapeople
slug: datapeople-eligibility
source_date: '2026-11-09'
source_filename: datapeople-eligibility.yml
source_heading: Eligibility
source_page: https://datapeople.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DataPeople\naid: datapeople\nurl: https://datapeople.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/datapeople/eligibility/datapeople-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from DataPeople's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Recruiting
- Human Resources
- Job Descriptions
- Talent Acquisition
- Hiring
- Analytics
- Artificial Intelligence
- ATS Integrations
---
