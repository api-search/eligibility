---
api_specs:
- filename: bloq-auth-api-openapi.yml
  format: yaml
  label: Bloq Auth API
  slug: bloq-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-auth-api-openapi.yml
- filename: bloq-bloq-api-api-openapi.yml
  format: yaml
  label: Bloq Bloq API
  slug: bloq-bloq-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-bloq-api-api-openapi.yml
- filename: bloq-chains-api-openapi.yml
  format: yaml
  label: Bloq Chains API
  slug: bloq-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-chains-api-openapi.yml
- filename: bloq-logs-api-openapi.yml
  format: yaml
  label: Bloq Logs API
  slug: bloq-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-logs-api-openapi.yml
- filename: bloq-staking-api-openapi.yml
  format: yaml
  label: Bloq Staking API
  slug: bloq-staking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-staking-api-openapi.yml
- filename: bloq-status-api-openapi.yml
  format: yaml
  label: Bloq Status API
  slug: bloq-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-status-api-openapi.yml
- filename: bloq-users-api-openapi.yml
  format: yaml
  label: Bloq Users API
  slug: bloq-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bloq/openapi/bloq-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Compliance Warranty: you represent you are not located in, under the control of, or a national or resident of any country to which the United States has embargoed goods or services'
  entity_types:
  - text: You must be at least 18 years of age to access or use our Services
    type: individual
  - text: If you are accessing or using our Services on behalf of another company or other legal entity, you represent that you are authorized to accept and bind that company or legal entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to access or use our Services
    value: '18'
  restricted_uses:
  - summary: Safety-critical systems
    text: None of the Services are designed for any use in a safety-critical system such that any malfunction or failure of a Service could cause serious personal injury or death
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
name: Bloq
provenance_date: '2026-11-09'
provider_name: Bloq
provider_slug: bloq
slug: bloq-eligibility
source_date: '2026-11-09'
source_filename: bloq-eligibility.yml
source_heading: Eligibility
source_page: https://bloq.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloq\naid: bloq\nurl: https://bloq.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Compliance Warranty: you represent you are not located in, under the control of, or a national or resident\n    of any country to which the United States has embargoed goods or services'\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to access or use our Services\n- type: business\n  text: If you are accessing or using our Services on behalf of another company or other legal entity, you represent\n    that you are authorized to accept and bind\
  \ that company or legal entity to these Terms.\nrestricted_uses:\n- summary: Safety-critical systems\n  text: None of the Services are designed for any use in a safety-critical system such that any malfunction or failure\n    of a Service could cause serious personal injury or death\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to access or use our Services\n"
source_yaml_url: https://artifacts.apis.io/bloq/eligibility/bloq-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bloq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web3
- Infrastructure
- DeFi
- Blockchain
---
