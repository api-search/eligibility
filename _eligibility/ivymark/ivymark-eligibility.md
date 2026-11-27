---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: interior designers, architects, builders and other professionals (“Pros”)
    type: business
  minimum_age:
    text: You are allowed to use the Ivy Platform if you are at least 16 years of age or if older, the minimum age lawfully allowed to use the Ivy Platform without parental consent.
    value: '16'
  restricted_uses:
  - summary: Soliciting minors' personal data
    text: solicit personal information from anyone under the age of 18
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
name: ivymark
provenance_date: '2026-11-09'
provider_name: ivymark
provider_slug: ivymark
slug: ivymark-eligibility
source_date: '2026-11-09'
source_filename: ivymark-eligibility.yml
source_heading: Eligibility
source_page: https://www.ivy.co/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ivymark\naid: ivymark\nurl: https://www.ivy.co/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: interior designers, architects, builders and other professionals (“Pros”)\nrestricted_uses:\n- summary: Soliciting minors' personal data\n  text: solicit personal information from anyone under the age of 18\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You are allowed to use the Ivy Platform if you are at least 16 years of age or if older, the\
  \ minimum age\n    lawfully allowed to use the Ivy Platform without parental consent.\n"
source_yaml_url: https://artifacts.apis.io/ivymark/eligibility/ivymark-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ivymark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Interior Design
- Business Management
- Design Software
- Product Sourcing
- Invoicing
- Payments
- Software-as-a-Service
---
