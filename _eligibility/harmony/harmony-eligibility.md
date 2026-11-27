---
api_specs:
- filename: harmony-tickets-api-openapi.yml
  format: yaml
  label: Harmony Tickets API
  slug: harmony-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/harmony/openapi/harmony-tickets-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If an individual is submitting an Order, or otherwise subscribing to the Service, using an organization's email address, such organization shall be deemed the Customer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive data
    text: Customer shall ensure that no Customer Content includes or links to Sensitive Data.
  - summary: No automated decisions with legal effect
    text: Customer shall not engage in any automatic decision-making (including, without limitation, profiling), or rely upon Output in isolation to make a decision, relating to any person, which has a legal effect or a similarly significant effect on that person.
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
name: Harmony
provenance_date: '2026-11-09'
provider_name: Harmony
provider_slug: harmony
slug: harmony-eligibility
source_date: '2026-11-09'
source_filename: harmony-eligibility.yml
source_heading: Eligibility
source_page: https://harmony.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Harmony\naid: harmony\nurl: https://harmony.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If an individual is submitting an Order, or otherwise subscribing to the Service, using an organization's\n    email address, such organization shall be deemed the Customer.\nrestricted_uses:\n- summary: No sensitive data\n  text: Customer shall ensure that no Customer Content includes or links to Sensitive Data.\n- summary: No automated decisions with legal effect\n  text: Customer shall not engage in any automatic\
  \ decision-making (including, without limitation, profiling), or\n    rely upon Output in isolation to make a decision, relating to any person, which has a legal effect or a similarly\n    significant effect on that person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/harmony/eligibility/harmony-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Harmony's own page on 2026-11-09.
synthetic: false
tags:
- ITSM
- Service Desk
- Ticketing
- Enterprise Service Management
- AI Agents
- IT Automation
- Help Desk
- Identity
- Company
---
