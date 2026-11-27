---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You affirm that You are either more than 18 years of age, or posses legal parental or guardian consent
    value: '18'
  restricted_uses:
  - summary: No commercial solicitation
    text: nor to use the Website for any commercial solicitation purposes
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
name: AuthMind
provenance_date: '2026-11-09'
provider_name: AuthMind
provider_slug: authmind
slug: authmind-eligibility
source_date: '2026-11-09'
source_filename: authmind-eligibility.yml
source_heading: Eligibility
source_page: https://www.authmind.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AuthMind\naid: authmind\nurl: https://www.authmind.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No commercial solicitation\n  text: nor to use the Website for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that You are either more than 18 years of age, or posses legal parental or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/authmind/eligibility/authmind-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from AuthMind's own page on 2026-11-09.
synthetic: false
tags:
- Identity
- Artificial Intelligence
- Security
- Observability
- Platform
---
