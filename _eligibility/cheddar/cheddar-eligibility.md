---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for use only by residents of the United States over the age of 13.
  minimum_age:
    text: By accessing or using the Site, you represent and warrant that you are at least thirteen (13) years of age.
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: You agree to use the Site, and to purchase services or products through the Site, for legitimate, non-commercial purposes only.
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
name: Cheddar
provenance_date: '2026-11-09'
provider_name: Cheddar
provider_slug: cheddar
slug: cheddar-eligibility
source_date: '2026-11-09'
source_filename: cheddar-eligibility.yml
source_heading: Eligibility
source_page: https://www.cheddar.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cheddar\naid: cheddar\nurl: https://www.cheddar.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for use only by residents of the United States over the age of 13.\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You agree to use the Site, and to purchase services or products through the Site, for legitimate, non-commercial\n    purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: By accessing or using the Site, you represent and warrant\
  \ that you are at least thirteen (13) years of age.\n"
source_yaml_url: https://artifacts.apis.io/cheddar/eligibility/cheddar-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cheddar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- News
- Business News
- Video
- Streaming
- Technology
- Finance
---
