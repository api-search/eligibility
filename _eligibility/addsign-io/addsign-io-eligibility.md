---
claim_count: 2
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
  - summary: Classified government documents
    text: 'Classified or Government Secrets: Documents with government classification levels'
  - summary: Regulated documents without verification
    text: Industries with specific compliance requirements (healthcare, government, defense) should verify AddSign meets their regulatory needs before use
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
name: AddSign
provenance_date: '2026-11-09'
provider_name: AddSign
provider_slug: addsign-io
slug: addsign-io-eligibility
source_date: '2026-11-09'
source_filename: addsign-io-eligibility.yml
source_heading: Eligibility
source_page: https://addsign.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AddSign\naid: addsign-io\nurl: https://addsign.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Classified government documents\n  text: 'Classified or Government Secrets: Documents with government classification levels'\n- summary: Regulated documents without verification\n  text: Industries with specific compliance requirements (healthcare, government, defense) should verify AddSign\n    meets their regulatory needs before use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/addsign-io/eligibility/addsign-io-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from AddSign's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- Small Business
- AI Document Analysis
- DocuSign Alternative
- Free Plan
---
