---
api_specs:
- filename: serval-auth-api-api-openapi.yml
  format: yaml
  label: Serval Auth API
  slug: serval-auth-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/serval/openapi/serval-auth-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Serval
    value: '18'
  restricted_uses:
  - summary: Violations of law or Terms
    text: Violate any applicable law or regulation
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
name: Serval
provenance_date: '2026-11-10'
provider_name: Serval
provider_slug: serval
slug: serval-eligibility
source_date: '2026-11-10'
source_filename: serval-eligibility.yml
source_heading: Eligibility
source_page: https://www.serval.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Serval\naid: serval\nurl: https://www.serval.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Violations of law or Terms\n  text: Violate any applicable law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n \
  \ text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Serval\n"
source_yaml_url: https://artifacts.apis.io/serval/eligibility/serval-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Serval's own page on 2026-11-10.
synthetic: false
tags:
- Company
- ITSM
- Help Desk
- Workflow Automation
- AI Agents
- Identity and Access Management
- Employee Support
- Ticketing
---
