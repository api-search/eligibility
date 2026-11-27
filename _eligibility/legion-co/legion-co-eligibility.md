---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: if you are a consumer resident in the province of Québec
  entity_types:
  - text: of legal age (18 years of age or older or otherwise of legal age in your jurisdiction, or, if you have parental consent, 13 years of age)
    type: individual
  minimum_age:
    text: of legal age (18 years of age or older or otherwise of legal age in your jurisdiction, or, if you have parental consent, 13 years of age)
    value: '18'
  restricted_uses:
  - summary: InstantPay limited to employees
    text: Only employees of participating employers are eligible to use InstantPay.
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
name: Legion
provenance_date: '2026-11-09'
provider_name: Legion
provider_slug: legion-co
slug: legion-co-eligibility
source_date: '2026-11-09'
source_filename: legion-co-eligibility.yml
source_heading: Eligibility
source_page: https://legion.co/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Legion\naid: legion-co\nurl: https://legion.co/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: if you are a consumer resident in the province of Québec\nentity_types:\n- type: individual\n  text: of legal age (18 years of age or older or otherwise of legal age in your jurisdiction, or, if you have parental\n    consent, 13 years of age)\nrestricted_uses:\n- summary: InstantPay limited to employees\n  text: Only employees of participating employers are eligible to use InstantPay.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: of legal age (18 years of age or older or otherwise of legal age in your jurisdiction, or, if you have parental\n    consent, 13 years of age)\n"
source_yaml_url: https://artifacts.apis.io/legion-co/eligibility/legion-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Legion's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Workforce
- Automation
- Artificial Intelligence
- Software-as-a-Service
---
