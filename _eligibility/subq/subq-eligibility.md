---
api_specs:
- filename: subq-openapi-generated.yml
  format: yaml
  label: Subquadratic API
  slug: subq-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subq/openapi/_ae-authored/subq-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered solely for business and commercial use.
    type: business
  - text: You must be at least 18 years old to create an account
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account
    value: '18'
  restricted_uses:
  - summary: Prohibited data types
    text: Submit prohibited data types as defined in our Usage Policy, including special categories of personal data, protected health information outside a BAA, or payment card data, without our prior written agreement
  - summary: Deceptive synthetic content
    text: Use the Services to generate misleading deepfakes, synthetic identities, or manipulated content designed to deceive
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
name: Subquadratic
provenance_date: '2026-11-10'
provider_name: Subquadratic
provider_slug: subq
slug: subq-eligibility
source_date: '2026-11-10'
source_filename: subq-eligibility.yml
source_heading: Eligibility
source_page: https://subq.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Subquadratic\naid: subq\nurl: https://subq.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are offered solely for business and commercial use.\n- type: individual\n  text: You must be at least 18 years old to create an account\nrestricted_uses:\n- summary: Prohibited data types\n  text: Submit prohibited data types as defined in our Usage Policy, including special categories of personal data,\n    protected health information outside a BAA, or payment card data, without our prior written agreement\n- summary: Deceptive\
  \ synthetic content\n  text: Use the Services to generate misleading deepfakes, synthetic identities, or manipulated content designed\n    to deceive\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account\n"
source_yaml_url: https://artifacts.apis.io/subq/eligibility/subq-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Subquadratic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Decision Models
- Long Context
---
