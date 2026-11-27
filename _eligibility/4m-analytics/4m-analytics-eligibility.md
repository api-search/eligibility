---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use this Website. By using this Website (and by agreeing to these Terms) you warrant and represent that you are at least 18 years old.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use this Website.
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
name: 4M Analytics
provenance_date: '2026-11-09'
provider_name: 4M Analytics
provider_slug: 4m-analytics
slug: 4m-analytics-eligibility
source_date: '2026-11-09'
source_filename: 4m-analytics-eligibility.yml
source_heading: Eligibility
source_page: https://www.4manalytics.com/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 4M Analytics\naid: 4m-analytics\nurl: https://www.4manalytics.com/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use this Website. By using this Website (and by agreeing to these\n    Terms) you warrant and represent that you are at least 18 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use this Website.\n"
source_yaml_url: https://artifacts.apis.io/4m-analytics/eligibility/4m-analytics-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from 4M Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Geospatial
- GIS
- Mapping
- Utilities
- Infrastructure
- Subsurface
- Location Intelligence
- Artificial Intelligence
- Construction Technology
---
