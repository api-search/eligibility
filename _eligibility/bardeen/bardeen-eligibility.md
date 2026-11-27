---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you can provide consent to data processing under the laws of your territory)
    type: individual
  - text: You also agree that you will not use the Services in connection with your professional endeavors (e.g., in connection with your work or employment) unless you have received express permission to do so.
    type: business
  minimum_age:
    text: You may use the Services only if you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Free plan non-commercial only
    text: The free plan offered by Bardeen (“Free Plan”) is intended solely for non-commercial and non-business purposes
  - summary: Professional use requires permission
    text: You also agree that you will not use the Services in connection with your professional endeavors (e.g., in connection with your work or employment) unless you have received express permission to do so.
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
name: Bardeen
provenance_date: '2026-11-09'
provider_name: Bardeen
provider_slug: bardeen
slug: bardeen-eligibility
source_date: '2026-11-09'
source_filename: bardeen-eligibility.yml
source_heading: Eligibility
source_page: https://www.bardeen.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bardeen\naid: bardeen\nurl: https://www.bardeen.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are at least 13 years of age (or such other minimum age at which you\n    can provide consent to data processing under the laws of your territory)\n- type: business\n  text: You also agree that you will not use the Services in connection with your professional endeavors (e.g.,\n    in connection with your work or employment) unless you have received express permission to do so.\nrestricted_uses:\n\
  - summary: Free plan non-commercial only\n  text: The free plan offered by Bardeen (“Free Plan”) is intended solely for non-commercial and non-business purposes\n- summary: Professional use requires permission\n  text: You also agree that you will not use the Services in connection with your professional endeavors (e.g.,\n    in connection with your work or employment) unless you have received express permission to do so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/bardeen/eligibility/bardeen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bardeen's own page on 2026-11-09.
synthetic: false
tags:
- AI Automation
- Workflow Automation
- Web Scraping
- Data Enrichment
- Browser Extension
- Sales Automation
- No-Code
- Go-To-Market
---
