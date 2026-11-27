---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: 'You are welcome to be our customer provided you agree to comply with our Acceptable Use Policy as set out in these Terms, and you are: over 18 years old live in the United Kingdom'
  entity_types:
  - text: a real, live person accessing our services for your personal use
    type: individual
  minimum_age:
    text: over 18 years old
    value: '18'
  restricted_uses:
  - summary: No commercial or business use
    text: (you can’t use our services for commercial or business use)
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Presenting a credit report and credit score is subject to you passing appropriate identity authentication for security purposes.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clearscore
provenance_date: '2026-11-09'
provider_name: Clearscore
provider_slug: clearscore
slug: clearscore-eligibility
source_date: '2026-11-09'
source_filename: clearscore-eligibility.yml
source_heading: Eligibility
source_page: https://www.clearscore.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clearscore\naid: clearscore\nurl: https://www.clearscore.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: 'You are welcome to be our customer provided you agree to comply with our Acceptable Use Policy as set out\n    in these Terms, and you are: over 18 years old live in the United Kingdom'\nentity_types:\n- type: individual\n  text: a real, live person accessing our services for your personal use\nrestricted_uses:\n- summary: No commercial or business use\n  text: (you can’t use our services for commercial or business use)\nverification:\n  kyc:\
  \ true\n  kyb: null\n  approval_required: null\n  text: Presenting a credit report and credit score is subject to you passing appropriate identity authentication\n    for security purposes.\nminimum_age:\n  value: '18'\n  text: over 18 years old\n"
source_yaml_url: https://artifacts.apis.io/clearscore/eligibility/clearscore-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Clearscore's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Credit
- Credit Score
- Fintech
- Financial Services
- Consumer Credit
- Open Banking
- Identity Protection
---
