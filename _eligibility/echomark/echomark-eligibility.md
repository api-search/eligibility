---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using this Website or EchoMark File Share, you represent and warrant that you are of legal age to form a binding contract with the Company.
    value: legal age
  restricted_uses:
  - summary: Users prohibited from receiving US-origin products
    text: You will not use the Website if you are prohibited from receiving products, services, or software originating from the United States
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
name: EchoMark
provenance_date: '2026-11-09'
provider_name: EchoMark
provider_slug: echomark
slug: echomark-eligibility
source_date: '2026-11-09'
source_filename: echomark-eligibility.yml
source_heading: Eligibility
source_page: https://www.echomark.com/terms-of-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EchoMark\naid: echomark\nurl: https://www.echomark.com/terms-of-services\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Users prohibited from receiving US-origin products\n  text: You will not use the Website if you are prohibited from receiving products, services, or software originating\n    from the United States\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: By using this Website or EchoMark File Share, you represent and warrant that you are of legal\
  \ age to form\n    a binding contract with the Company.\n"
source_yaml_url: https://artifacts.apis.io/echomark/eligibility/echomark-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from EchoMark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Information Security
- Forensic Watermarking
- Insider Threat
- Data Loss Prevention
- Leak Detection
---
