---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: The Site is intended for use by those who can access it from within the UK.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Phishing
    text: not to use the Site to simulate communications from us or another service or entity in order to collect identity information, authentication credentials, or other information (‘phishing’);
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
name: Tradefeedr
provenance_date: '2026-11-10'
provider_name: Tradefeedr
provider_slug: tradefeedr
slug: tradefeedr-eligibility
source_date: '2026-11-10'
source_filename: tradefeedr-eligibility.yml
source_heading: Eligibility
source_page: https://www.tradefeedr.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tradefeedr\naid: tradefeedr\nurl: https://www.tradefeedr.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: The Site is intended for use by those who can access it from within the UK.\nentity_types: []\nrestricted_uses:\n- summary: Phishing\n  text: not to use the Site to simulate communications from us or another service or entity in order to collect\n    identity information, authentication credentials, or other information (‘phishing’);\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tradefeedr/eligibility/tradefeedr-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Tradefeedr's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Data
- Trading
- Analytics
- Platform
---
