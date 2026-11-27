---
claim_count: 2
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
  - summary: Illegal purposes
    text: Use the Service for any illegal purpose
  - summary: Malicious code
    text: Use the Service to store or transmit malicious code
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
name: AnalyticLabs
provenance_date: '2026-11-09'
provider_name: AnalyticLabs
provider_slug: aldc-io
slug: aldc-io-eligibility
source_date: '2026-11-09'
source_filename: aldc-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.analyticlabs.io/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnalyticLabs\naid: aldc-io\nurl: https://www.analyticlabs.io/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the Service for any illegal purpose\n- summary: Malicious code\n  text: Use the Service to store or transmit malicious code\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aldc-io/eligibility/aldc-io-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from AnalyticLabs's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Analytics
- Data
- Business Intelligence
- Platform
---
