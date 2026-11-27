---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that the Website is appropriate or available for use outside of the United States. Access to the Website from countries or territories or by individuals where such access is illegal is prohibited.
  minimum_age:
    text: You represent that you are over the age of 18.
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
name: Campus
provenance_date: '2026-11-09'
provider_name: Campus
provider_slug: campus
slug: campus-eligibility
source_date: '2026-11-09'
source_filename: campus-eligibility.yml
source_heading: Eligibility
source_page: https://campus.edu/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Campus\naid: campus\nurl: https://campus.edu/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that the Website is appropriate or available for use outside of the United States.\n    Access to the Website from countries or territories or by individuals where such access is illegal is prohibited.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/campus/eligibility/campus-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Campus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Higher Education
- E-Learning
- Community College
- EdTech
- Accredited Degrees
---
