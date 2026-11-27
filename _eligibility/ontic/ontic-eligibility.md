---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be 13 years or older to request information or to be contacted by Ontic.
    value: '13'
  restricted_uses:
  - summary: Hate speech and abusive language
    text: Hate speech of any kind is grounds for immediate and permanent suspension of access to all or part of the Site.
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
name: Ontic
provenance_date: '2026-11-10'
provider_name: Ontic
provider_slug: ontic
slug: ontic-eligibility
source_date: '2026-11-10'
source_filename: ontic-eligibility.yml
source_heading: Eligibility
source_page: https://ontic.co/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ontic\naid: ontic\nurl: https://ontic.co/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Hate speech and abusive language\n  text: Hate speech of any kind is grounds for immediate and permanent suspension of access to all or part of the\n    Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to request information or to be contacted by Ontic.\n"
source_yaml_url: https://artifacts.apis.io/ontic/eligibility/ontic-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Ontic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Physical Security
- Protective Intelligence
- Threat Intelligence
- Executive Protection
- Incident Management
- Corporate Investigations
- GSOC
- Risk Management
---
