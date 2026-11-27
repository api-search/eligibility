---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes prohibited
    text: or use it for unlawful purposes
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
name: DDMarketer
provenance_date: '2026-11-09'
provider_name: DDMarketer
provider_slug: ddmarketer
slug: ddmarketer-eligibility
source_date: '2026-11-09'
source_filename: ddmarketer-eligibility.yml
source_heading: Eligibility
source_page: https://www.ddmarketer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DDMarketer\naid: ddmarketer\nurl: https://www.ddmarketer.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes prohibited\n  text: or use it for unlawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/ddmarketer/eligibility/ddmarketer-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from DDMarketer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Market Research
- OpportunityValidation
- AI Integration
---
