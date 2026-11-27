---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: as a natural person (the “ Customer ”)
    type: individual
  - text: on behalf of the legal entity you represent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or illicit activities
    text: using the Services in connection with and/or for the purpose of carrying out, directly or indirectly, illegal or illicit activities
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
name: Stonly
provenance_date: '2026-11-10'
provider_name: Stonly
provider_slug: stonly
slug: stonly-eligibility
source_date: '2026-11-10'
source_filename: stonly-eligibility.yml
source_heading: Eligibility
source_page: https://stonly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stonly\naid: stonly\nurl: https://stonly.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: as a natural person (the “ Customer ”)\n- type: business\n  text: on behalf of the legal entity you represent\nrestricted_uses:\n- summary: Illegal or illicit activities\n  text: using the Services in connection with and/or for the purpose of carrying out, directly or indirectly, illegal\n    or illicit activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stonly/eligibility/stonly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Stonly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Knowledge Base
- Knowledge Management
- Customer Service
- Self-Service
- Help Center
- AI Chatbot
- Mobile SDK
- Customer Experience
---
