---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age or the age of legal majority in your jurisdiction, whichever is greater, to use the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age or the age of legal majority in your jurisdiction, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Unlawful, fraudulent or malicious use
    text: Use the Site for any unlawful, fraudulent, or malicious purpose
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
name: Radar
provenance_date: '2026-11-09'
provider_name: Radar
provider_slug: goradar-com
slug: goradar-com-eligibility
source_date: '2026-11-09'
source_filename: goradar-com-eligibility.yml
source_heading: Eligibility
source_page: https://goradar.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Radar\naid: goradar-com\nurl: https://goradar.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age or the age of legal majority in your jurisdiction, whichever is greater,\n    to use the Site.\nrestricted_uses:\n- summary: Unlawful, fraudulent or malicious use\n  text: Use the Site for any unlawful, fraudulent, or malicious purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years\
  \ of age or the age of legal majority in your jurisdiction, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/goradar-com/eligibility/goradar-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Radar's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- RFID
- Inventory
- Automation
---
