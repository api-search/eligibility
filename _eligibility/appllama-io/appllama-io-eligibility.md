---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A Pro plan is licensed to one named individual for their own use.
    type: individual
  - text: Where access is required for more than one person, a team account applies. Contact us and we will arrange it.
    type: business
  minimum_age:
    text: You must be old enough to enter into a contract in your jurisdiction.
    value: null
  restricted_uses:
  - summary: No credential sharing
    text: Sharing account credentials, or allowing another person to use your account, is not permitted.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with a one-time code sent to your email address, or with a connected Google, Apple or X account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Appllama
provenance_date: '2026-11-09'
provider_name: Appllama
provider_slug: appllama-io
slug: appllama-io-eligibility
source_date: '2026-11-09'
source_filename: appllama-io-eligibility.yml
source_heading: Eligibility
source_page: https://appllama.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appllama\naid: appllama-io\nurl: https://appllama.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A Pro plan is licensed to one named individual for their own use.\n- type: business\n  text: Where access is required for more than one person, a team account applies. Contact us and we will arrange\n    it.\nrestricted_uses:\n- summary: No credential sharing\n  text: Sharing account credentials, or allowing another person to use your account, is not permitted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: You sign in with a one-time code sent to your email address, or with a connected Google, Apple or X account.\nminimum_age:\n  value: null\n  text: You must be old enough to enter into a contract in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/appllama-io/eligibility/appllama-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Appllama's own page on 2026-11-09.
synthetic: false
tags:
- Design
- UI/UX
- Mobile
- Screens
- Marketplace
---
