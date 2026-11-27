---
api_specs:
- filename: infere-openapi-generated.yml
  format: yaml
  label: Snowball Studio Ltd. API
  slug: infere-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infere/openapi/_ae-authored/infere-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, incorporated in, or ordinarily resident in any jurisdiction subject to comprehensive trade sanctions imposed by the European Union, United States, United Kingdom, or United Nations
  entity_types:
  - text: If you access the Service in the course of business (including on behalf of an entity), you are a Business User and these Terms apply as B2B terms.
    type: business
  - text: If you are a natural person acting outside your trade/business, you are a Consumer and the additional mandatory consumer protections in Annex E (Consumer Terms) apply.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to create an Account.
    value: '18'
  restricted_uses:
  - summary: High-risk or safety-critical decisions
    text: use the Service for high-risk or safety-critical decisions without appropriate human oversight
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
name: Snowball Studio Ltd.
provenance_date: '2026-11-09'
provider_name: Snowball Studio Ltd.
provider_slug: infere
slug: infere-eligibility
source_date: '2026-11-09'
source_filename: infere-eligibility.yml
source_heading: Eligibility
source_page: https://infere.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snowball Studio Ltd.\naid: infere\nurl: https://infere.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, incorporated in, or ordinarily resident in any jurisdiction\n    subject to comprehensive trade sanctions imposed by the European Union, United States, United Kingdom, or United\n    Nations\nentity_types:\n- type: business\n  text: If you access the Service in the course of business (including on behalf of an entity), you are a Business\n    User and these Terms apply as B2B terms.\n- type: individual\n  text:\
  \ If you are a natural person acting outside your trade/business, you are a Consumer and the additional mandatory\n    consumer protections in Annex E (Consumer Terms) apply.\nrestricted_uses:\n- summary: High-risk or safety-critical decisions\n  text: use the Service for high-risk or safety-critical decisions without appropriate human oversight\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to create an Account.\n"
source_yaml_url: https://artifacts.apis.io/infere/eligibility/infere-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Snowball Studio Ltd.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Observability
- Prompt Management
- LLM
---
