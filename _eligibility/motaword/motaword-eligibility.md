---
api_specs:
- filename: motaword-api-openapi.yml
  format: yaml
  label: MotaWord API API
  slug: motaword-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/motaword/openapi/_original/motaword-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to use our website.
    value: '18'
  restricted_uses:
  - summary: Automated data collection without consent
    text: You must not conduct any systematic or automated data collection activities (including, without limitation, scraping, data mining, data extraction and data harvesting) on or in relation to our website without our express written consent.
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
name: MotaWord
provenance_date: '2026-11-10'
provider_name: MotaWord
provider_slug: motaword
slug: motaword-eligibility
source_date: '2026-11-10'
source_filename: motaword-eligibility.yml
source_heading: Eligibility
source_page: https://www.motaword.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MotaWord\naid: motaword\nurl: https://www.motaword.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Automated data collection without consent\n  text: You must not conduct any systematic or automated data collection activities (including, without limitation,\n    scraping, data mining, data extraction and data harvesting) on or in relation to our website without our express\n    written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ You must be at least 18 years old to use our website.\n"
source_yaml_url: https://artifacts.apis.io/motaword/eligibility/motaword-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from MotaWord's own page on 2026-11-10.
synthetic: false
tags:
- Translation
- Localization
- Artificial Intelligence
- Software-as-a-Service
- Enterprise
---
