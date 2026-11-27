---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be 18 years of age or older to access or use our Services.
    value: '18'
  restricted_uses:
  - summary: No sensitive regulated data
    text: You must not use the Services to upload, store or process sensitive categories of data, including payment card data subject to PCI DSS
  - summary: No PHI without BAA
    text: Protected Health Information (PHI) as defined by HIPAA, except where (i) a Business Associate Agreement (BAA) has been duly executed between Internxt and the Customer
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
name: Internxt
provenance_date: '2026-11-09'
provider_name: Internxt
provider_slug: internxt
slug: internxt-eligibility
source_date: '2026-11-09'
source_filename: internxt-eligibility.yml
source_heading: Eligibility
source_page: https://internxt.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Internxt\naid: internxt\nurl: https://internxt.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No sensitive regulated data\n  text: You must not use the Services to upload, store or process sensitive categories of data, including payment\n    card data subject to PCI DSS\n- summary: No PHI without BAA\n  text: Protected Health Information (PHI) as defined by HIPAA, except where (i) a Business Associate Agreement\n    (BAA) has been duly executed between Internxt and the Customer\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to access or use our Services.\n"
source_yaml_url: https://artifacts.apis.io/internxt/eligibility/internxt-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Internxt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Storage
- Encryption
- Privacy
- Europe
---
