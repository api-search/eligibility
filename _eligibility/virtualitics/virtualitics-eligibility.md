---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company makes no representation that any of the materials or the services to which you have been given access are available or appropriate for use in other locations.
  minimum_age:
    text: You agree that by using the site you represent that you are at least 18 years old and that you are legally able to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: Unsolicited e-mail
    text: using the Site to send unsolicited e-mail, including, without limitation, promotions, or advertisements for products or services
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
name: Virtualitics
provenance_date: '2026-11-10'
provider_name: Virtualitics
provider_slug: virtualitics
slug: virtualitics-eligibility
source_date: '2026-11-10'
source_filename: virtualitics-eligibility.yml
source_heading: Eligibility
source_page: https://virtualitics.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Virtualitics\naid: virtualitics\nurl: https://virtualitics.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company makes no representation that any of the materials or the services to which you have been given\n    access are available or appropriate for use in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited e-mail\n  text: using the Site to send unsolicited e-mail, including, without limitation, promotions, or advertisements\n    for products or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You agree that by using the site you represent that you are at least 18 years old and that you are legally\n    able to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/virtualitics/eligibility/virtualitics-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Virtualitics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Data Analytics
- Data Visualization
- Machine Learning
- Defense
- Government
- Python
- SDK
- Command Line Interface
---
