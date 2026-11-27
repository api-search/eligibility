---
api_specs:
- filename: vezgo-openapi-generated.yml
  format: yaml
  label: Vezgo API
  slug: vezgo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vezgo/openapi/_ae-authored/vezgo-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This section applies to organizations (“Enterprise Clients”) who use the Vezgo API or embed Vezgo services in their applications for end-users.
    type: business
  - text: 'Client : An organization or individual using the Services to manage or access Data, including Enterprise Clients.'
    type: individual
  minimum_age:
    text: You are at least 13 years old;
    value: '13'
  restricted_uses:
  - summary: End-user data use limits
    text: Enterprise Clients may only use end-user data to deliver services to those users.
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
name: Vezgo
provenance_date: '2026-11-10'
provider_name: Vezgo
provider_slug: vezgo
slug: vezgo-eligibility
source_date: '2026-11-10'
source_filename: vezgo-eligibility.yml
source_heading: Eligibility
source_page: https://vezgo.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vezgo\naid: vezgo\nurl: https://vezgo.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This section applies to organizations (“Enterprise Clients”) who use the Vezgo API or embed Vezgo services\n    in their applications for end-users.\n- type: individual\n  text: 'Client : An organization or individual using the Services to manage or access Data, including Enterprise\n    Clients.'\nrestricted_uses:\n- summary: End-user data use limits\n  text: Enterprise Clients may only use end-user data to deliver services to\
  \ those users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are at least 13 years old;\n"
source_yaml_url: https://artifacts.apis.io/vezgo/eligibility/vezgo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vezgo's own page on 2026-11-10.
synthetic: false
tags:
- Cryptocurrency
- Data API
- Digital Assets
- Fintech
- Portfolio Tracking
---
