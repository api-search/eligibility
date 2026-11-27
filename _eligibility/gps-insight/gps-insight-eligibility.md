---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We may restrict access to portions of the Services in certain countries.
  minimum_age:
    text: null
    value: null
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
name: GPS Insight
provenance_date: '2026-11-09'
provider_name: GPS Insight
provider_slug: gps-insight
slug: gps-insight-eligibility
source_date: '2026-11-09'
source_filename: gps-insight-eligibility.yml
source_heading: Eligibility
source_page: https://www.gpsinsight.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GPS Insight\naid: gps-insight\nurl: https://www.gpsinsight.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We may restrict access to portions of the Services in certain countries.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gps-insight/eligibility/gps-insight-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from GPS Insight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fleet Management
- GPS Tracking
- Telematics
- Software-as-a-Service
---
