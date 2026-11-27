---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Only persons aged 16 years and older may use this Site.
    value: '16'
  restricted_uses:
  - summary: No solicitation of unauthorized products
    text: Nothing on this Site should be construed as a solicitation or promotion for any product which is not authorized by the laws and regulations of the state or country where you are located
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
name: Nuvaira
provenance_date: '2026-11-10'
provider_name: Nuvaira
provider_slug: nuvaira
slug: nuvaira-eligibility
source_date: '2026-11-10'
source_filename: nuvaira-eligibility.yml
source_heading: Eligibility
source_page: https://nuvaira.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nuvaira\naid: nuvaira\nurl: https://nuvaira.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No solicitation of unauthorized products\n  text: Nothing on this Site should be construed as a solicitation or promotion for any product which is not authorized\n    by the laws and regulations of the state or country where you are located\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Only persons aged 16 years and older may use this Site.\n"
source_yaml_url: https://artifacts.apis.io/nuvaira/eligibility/nuvaira-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Nuvaira's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Health
- Healthcare
- Respiratory
- COPD
- Pulmonology
- Clinical Trials
- Medical Technology
---
