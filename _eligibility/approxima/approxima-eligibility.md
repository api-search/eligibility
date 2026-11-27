---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized testing targets
    text: you represent and warrant that you are the owner of, or are authorized to test, the website or application at that URL
  - summary: Highly sensitive personal data
    text: you should not use the Service to test pages containing highly sensitive personal data (e.g., medical records, financial statements) unless you are comfortable with this data flowing through third-party AI APIs
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Approxima
provenance_date: '2026-11-09'
provider_name: Approxima
provider_slug: approxima
slug: approxima-eligibility
source_date: '2026-11-09'
source_filename: approxima-eligibility.yml
source_heading: Eligibility
source_page: https://approxima.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Approxima\naid: approxima\nurl: https://approxima.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized testing targets\n  text: you represent and warrant that you are the owner of, or are authorized to test, the website or application\n    at that URL\n- summary: Highly sensitive personal data\n  text: you should not use the Service to test pages containing highly sensitive personal data (e.g., medical records,\n    financial statements) unless you are comfortable with this data flowing through third-party AI APIs\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address to create an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/approxima/eligibility/approxima-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Approxima's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software Development
- AI Agents
- Testing
- QA
- CI/CD
- Pull Request
- Developer Tools
- Y Combinator
---
