---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: the User declares to be of legal age, in accordance with their own legislation
    value: legal age
  restricted_uses:
  - summary: illicit or harmful use
    text: The User undertakes not to use the Website for illicit purposes
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
name: Bigle
provenance_date: '2026-11-09'
provider_name: Bigle
provider_slug: bigle
slug: bigle-eligibility
source_date: '2026-11-09'
source_filename: bigle-eligibility.yml
source_heading: Eligibility
source_page: https://www.biglelegal.com/en/policies/legal-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bigle\naid: bigle\nurl: https://www.biglelegal.com/en/policies/legal-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: illicit or harmful use\n  text: The User undertakes not to use the Website for illicit purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: the User declares to be of legal age, in accordance with their own legislation\n"
source_yaml_url: https://artifacts.apis.io/bigle/eligibility/bigle-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Bigle's own page on 2026-11-09.
synthetic: false
tags:
- Contract Lifecycle Management
- Legal Tech
- E-Signature
- Generative AI
- Real Estate
- Corporations
- Law Firms
- Notaries
---
