---
api_specs:
- filename: clawcall-dev-openapi-generated.yml
  format: yaml
  label: ClawCall API
  slug: clawcall-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawcall-dev/openapi/_ae-authored/clawcall-dev-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: ClawCall places outbound calls to United States (+1) phone numbers only. Inbound SMS that starts a call is supported from US and Canadian numbers, but outbound calling remains US-only.
  entity_types:
  - text: If you use ClawCall on behalf of a company or another person, you represent that you have authority to bind that party and to provide call instructions on their behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No emergency use
    text: ClawCall is not an emergency service.
  - summary: Not professional advice substitute
    text: Do not use ClawCall as a substitute for professional medical, legal, financial, tax, insurance, emergency, or safety-critical advice or action.
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
name: ClawCall
provenance_date: '2026-11-09'
provider_name: ClawCall
provider_slug: clawcall-dev
slug: clawcall-dev-eligibility
source_date: '2026-11-09'
source_filename: clawcall-dev-eligibility.yml
source_heading: Eligibility
source_page: https://clawcall.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClawCall\naid: clawcall-dev\nurl: https://clawcall.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: ClawCall places outbound calls to United States (+1) phone numbers only. Inbound SMS that starts a call\n    is supported from US and Canadian numbers, but outbound calling remains US-only.\nentity_types:\n- type: business\n  text: If you use ClawCall on behalf of a company or another person, you represent that you have authority to bind\n    that party and to provide call instructions on their behalf.\nrestricted_uses:\n- summary: No emergency use\n  text: ClawCall is\
  \ not an emergency service.\n- summary: Not professional advice substitute\n  text: Do not use ClawCall as a substitute for professional medical, legal, financial, tax, insurance, emergency,\n    or safety-critical advice or action.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clawcall-dev/eligibility/clawcall-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from ClawCall's own page on 2026-11-09.
synthetic: false
tags:
- AI Phone Calls
- Developer Tools
- ChatGPT Plugins
- US Phone Numbers
---
