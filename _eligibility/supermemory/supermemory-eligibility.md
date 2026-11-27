---
api_specs:
- filename: supermemory-openapi.json
  format: json
  label: Supermemory API
  slug: supermemory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/supermemory/openapi/supermemory-openapi.json
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country subject to comprehensive sanctions.
  entity_types:
  - text: You must be at least 18 years old and have the legal capacity to enter into this agreement.
    type: individual
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have the legal capacity to enter into this agreement.
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful activities
    text: Use the Services for illegal activities or to violate any laws
  - summary: Harm to minors
    text: Engage in activities that could harm minors
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
name: Supermemory
provenance_date: '2026-11-10'
provider_name: Supermemory
provider_slug: supermemory
slug: supermemory-eligibility
source_date: '2026-11-10'
source_filename: supermemory-eligibility.yml
source_heading: Eligibility
source_page: https://supermemory.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Supermemory\naid: supermemory\nurl: https://supermemory.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country subject to comprehensive sanctions.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have the legal capacity to enter into this agreement.\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind such entity to these Terms.\nrestricted_uses:\n- summary: Illegal or harmful activities\n\
  \  text: Use the Services for illegal activities or to violate any laws\n- summary: Harm to minors\n  text: Engage in activities that could harm minors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have the legal capacity to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/supermemory/eligibility/supermemory-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Supermemory's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Agents
- Platform
---
