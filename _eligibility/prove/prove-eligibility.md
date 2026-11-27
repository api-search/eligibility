---
api_specs:
- filename: prove-auth-api-openapi.yml
  format: yaml
  label: Prove Auth API
  slug: prove-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-auth-api-openapi.yml
- filename: prove-authentication-api-openapi.yml
  format: yaml
  label: Prove Authentication API
  slug: prove-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-authentication-api-openapi.yml
- filename: prove-domain-api-openapi.yml
  format: yaml
  label: Prove Domain API
  slug: prove-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-domain-api-openapi.yml
- filename: prove-identity-api-openapi.yml
  format: yaml
  label: Prove Identity API
  slug: prove-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-identity-api-openapi.yml
- filename: prove-identity-verification-api-openapi.yml
  format: yaml
  label: Prove Identity Verification API
  slug: prove-identity-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-identity-verification-api-openapi.yml
- filename: prove-pre-fill-api-openapi.yml
  format: yaml
  label: Prove Pre-Fill API
  slug: prove-pre-fill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-pre-fill-api-openapi.yml
- filename: prove-trust-score-api-openapi.yml
  format: yaml
  label: Prove Trust Score API
  slug: prove-trust-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prove/openapi/prove-trust-score-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Prove is a business-to-business company and does not direct the Site to consumers or children.
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old
    value: '18'
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
name: Prove
provenance_date: '2026-11-10'
provider_name: Prove
provider_slug: prove
slug: prove-eligibility
source_date: '2026-11-10'
source_filename: prove-eligibility.yml
source_heading: Eligibility
source_page: https://www.prove.com/legal/prove-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prove\naid: prove\nurl: https://www.prove.com/legal/prove-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Prove is a business-to-business company and does not direct the Site to consumers or children.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/prove/eligibility/prove-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Prove's own page on 2026-11-10.
synthetic: false
tags:
- Identity Verification
- Authentication
- Phone Intelligence
- KYC
- Fraud Prevention
---
