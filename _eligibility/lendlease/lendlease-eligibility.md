---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are at least 18 years of age or, if you are under 18 years of age (a “Minor”), that you are using the Website with the consent of your parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: Anti-social, illegal or disruptive use
    text: In accessing this Website, you must act in accordance with the law and in a manner that is not otherwise anti-social
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
name: Lendlease
provenance_date: '2026-11-09'
provider_name: Lendlease
provider_slug: lendlease
slug: lendlease-eligibility
source_date: '2026-11-09'
source_filename: lendlease-eligibility.yml
source_heading: Eligibility
source_page: https://www.lendlease.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lendlease\naid: lendlease\nurl: https://www.lendlease.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Anti-social, illegal or disruptive use\n  text: In accessing this Website, you must act in accordance with the law and in a manner that is not otherwise\n    anti-social\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age or, if you are under 18 years of age (a “Minor”), that you are using the\n    Website with\
  \ the consent of your parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/lendlease/eligibility/lendlease-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Lendlease's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Construction
- Property Development
- Investment Management
- Australia
- ASX Listed
---
