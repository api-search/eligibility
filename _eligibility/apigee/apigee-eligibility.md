---
api_specs:
- filename: apigee-hybrid-api-openapi.yml
  format: yaml
  label: Apigee Hybrid API
  slug: apigee-hybrid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apigee/openapi/apigee-hybrid-api-openapi.yml
- filename: apigee-organizations-api-openapi.yml
  format: yaml
  label: Apigee Organizations API
  slug: apigee-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apigee/openapi/apigee-organizations-api-openapi.yml
- filename: apigee-projects-api-openapi.yml
  format: yaml
  label: Apigee Projects API
  slug: apigee-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apigee/openapi/apigee-projects-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting on behalf of Customer, you represent and warrant that (i) you have full legal authority to bind Customer to this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Activities
    text: access or use the Services or any AI Agent (i) for High Risk Activities
  - summary: ITAR-controlled materials
    text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR) maintained by the United States Department of State
  - summary: Export control violations
    text: (viii) in a manner that breaches, or causes the breach of, Export Control Laws
  - summary: Health information without BAA
    text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must have an Account to use the Services and is responsible for the information it provides to create the Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Apigee
provenance_date: '2026-11-09'
provider_name: Apigee
provider_slug: apigee
slug: apigee-eligibility
source_date: '2026-11-09'
source_filename: apigee-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apigee\naid: apigee\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting on behalf of Customer, you represent and warrant that (i) you have full legal authority\n    to bind Customer to this Agreement\nrestricted_uses:\n- summary: High Risk Activities\n  text: access or use the Services or any AI Agent (i) for High Risk Activities\n- summary: ITAR-controlled materials\n  text: (vii) for materials or activities that are subject to the International Traffic in Arms\
  \ Regulations (ITAR)\n    maintained by the United States Department of State\n- summary: Export control violations\n  text: (viii) in a manner that breaches, or causes the breach of, Export Control Laws\n- summary: Health information without BAA\n  text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except\n    as permitted by an executed HIPAA BAA\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must have an Account to use the Services and is responsible for the information it provides to\n    create the Account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apigee/eligibility/apigee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Apigee's own page on 2026-11-09.
synthetic: false
tags:
- Apigee
- Advanced API Security
- AI Agents
- Analytics
- API Gateway
- API Governance
- API Hub
- API Management
- Developer Portal
- Enterprise
- Generative AI
- Hybrid
- Integration
- Microservices
- MCP
- Monetization
---
