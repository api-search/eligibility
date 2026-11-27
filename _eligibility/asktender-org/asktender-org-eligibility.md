---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: askTender is for businesses. It is not offered to consumers
    type: business
  minimum_age:
    text: you must be at least 18 years old to use it
    value: '18'
  restricted_uses:
  - summary: Sanctions and export controls
    text: use askTender in breach of sanctions, export controls or procurement law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a one-time code sent to your work email.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: askTender
provenance_date: '2026-11-09'
provider_name: askTender
provider_slug: asktender-org
slug: asktender-org-eligibility
source_date: '2026-11-09'
source_filename: asktender-org-eligibility.yml
source_heading: Eligibility
source_page: https://asktender.org/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: askTender\naid: asktender-org\nurl: https://asktender.org/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: askTender is for businesses. It is not offered to consumers\nrestricted_uses:\n- summary: Sanctions and export controls\n  text: use askTender in breach of sanctions, export controls or procurement law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with a one-time code sent to your work email.\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old to use it\n"
source_yaml_url: https://artifacts.apis.io/asktender-org/eligibility/asktender-org-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from askTender's own page on 2026-11-09.
synthetic: false
tags:
- Procurement
- Government
- B2B
- Software-as-a-Service
- Marketplace
---
