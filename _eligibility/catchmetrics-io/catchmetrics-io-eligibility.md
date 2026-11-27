---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old or the age of majority in your jurisdiction to use our Services.
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
name: Catch Metrics
provenance_date: '2026-11-09'
provider_name: Catch Metrics
provider_slug: catchmetrics-io
slug: catchmetrics-io-eligibility
source_date: '2026-11-09'
source_filename: catchmetrics-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.catchmetrics.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Catch Metrics\naid: catchmetrics-io\nurl: https://www.catchmetrics.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of majority in your jurisdiction to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/catchmetrics-io/eligibility/catchmetrics-io-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Catch Metrics's own page on 2026-11-09.
synthetic: false
tags:
- Web Performance
- Monitoring
- Analytics
- Software-as-a-Service
- Performance Optimization
- Company
---
