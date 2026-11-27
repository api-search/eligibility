---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use our Services or of legal age to form a binding contract in your jurisdiction if that age is greater than 18 years old.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use our Services
    value: '18'
  restricted_uses:
  - summary: Spam, illegal activity, infringement
    text: You are prohibited from using our services to send spam, conduct illegal activities, or infringe upon the rights of others.
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
name: Adflipr
provenance_date: '2026-11-09'
provider_name: Adflipr
provider_slug: adflipr-com
slug: adflipr-com-eligibility
source_date: '2026-11-09'
source_filename: adflipr-com-eligibility.yml
source_heading: Eligibility
source_page: https://adflipr.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adflipr\naid: adflipr-com\nurl: https://adflipr.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use our Services or of legal age to form a binding contract in your\n    jurisdiction if that age is greater than 18 years old.\nrestricted_uses:\n- summary: Spam, illegal activity, infringement\n  text: You are prohibited from using our services to send spam, conduct illegal activities, or infringe upon the\n    rights of others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Services\n"
source_yaml_url: https://artifacts.apis.io/adflipr-com/eligibility/adflipr-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Adflipr's own page on 2026-11-09.
synthetic: false
tags:
- Email Marketing
- Automation
- E-Commerce
- Software-as-a-Service
- Marketing
---
