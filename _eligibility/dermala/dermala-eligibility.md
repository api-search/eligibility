---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This website is not for use by any minors (defined as those who are not at least 18 years of age).
    value: '18'
  restricted_uses:
  - summary: No minors
    text: This website is not for use by any minors (defined as those who are not at least 18 years of age).
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
name: Dermala
provenance_date: '2026-11-09'
provider_name: Dermala
provider_slug: dermala
slug: dermala-eligibility
source_date: '2026-11-09'
source_filename: dermala-eligibility.yml
source_heading: Eligibility
source_page: https://www.dermala.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dermala\naid: dermala\nurl: https://www.dermala.com/pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No minors\n  text: This website is not for use by any minors (defined as those who are not at least 18 years of age).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This website is not for use by any minors (defined as those who are not at least 18 years of age).\n"
source_yaml_url: https://artifacts.apis.io/dermala/eligibility/dermala-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Dermala's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Skincare
- Microbiome
- E-Commerce
---
