---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal use only
    text: Customer is prohibited from reselling, sublicensing, or sharing Portfolio Analytics outputs, data, or access with third parties without AlphaGeo’s prior written consent.
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
name: Alphageo
provenance_date: '2026-11-09'
provider_name: Alphageo
provider_slug: alphageo
slug: alphageo-eligibility
source_date: '2026-11-09'
source_filename: alphageo-eligibility.yml
source_heading: Eligibility
source_page: https://alphageo.ai/service-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alphageo\naid: alphageo\nurl: https://alphageo.ai/service-agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Internal use only\n  text: Customer is prohibited from reselling, sublicensing, or sharing Portfolio Analytics outputs, data, or access\n    with third parties without AlphaGeo’s prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alphageo/eligibility/alphageo-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Alphageo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Climate
- Climate Risk
- Geospatial
- Analytics
- Risk Management
- Real Estate
- ESG
- Data
- Machine Learning
---
