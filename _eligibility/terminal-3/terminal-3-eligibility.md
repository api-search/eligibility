---
api_specs:
- filename: terminal-3-did-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 DID V1 API
  slug: terminal-3-did-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-did-v1-api-openapi.yml
- filename: terminal-3-openid-connect-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 OpenID Connect V1 API
  slug: terminal-3-openid-connect-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-openid-connect-v1-api-openapi.yml
- filename: terminal-3-openid-connect-v2-api-openapi.yml
  format: yaml
  label: Terminal 3 OpenID Connect V2 API
  slug: terminal-3-openid-connect-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-openid-connect-v2-api-openapi.yml
- filename: terminal-3-sub-client-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 Sub Client V1 API
  slug: terminal-3-sub-client-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-sub-client-v1-api-openapi.yml
- filename: terminal-3-transactional-email-template-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 Transactional Email Template V1 API
  slug: terminal-3-transactional-email-template-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-transactional-email-template-v1-api-openapi.yml
- filename: terminal-3-user-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 User V1 API
  slug: terminal-3-user-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-user-v1-api-openapi.yml
- filename: terminal-3-vc-v1-api-openapi.yml
  format: yaml
  label: Terminal 3 VC V1 API
  slug: terminal-3-vc-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/terminal-3/openapi/terminal-3-vc-v1-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided through the Services is not intended for distribution to, or use by, any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: You must be at least 18 years old and must have reached the age of majority in the jurisdiction in which you reside
    type: individual
  - text: where you act on behalf of another person or an entity, that you have the authority to bind that person or entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and must have reached the age of majority in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: use the Services for any unlawful purpose or in any manner inconsistent with applicable law or regulation
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Verification of your identity may be performed by independent third-party providers
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Terminal 3
provenance_date: '2026-11-10'
provider_name: Terminal 3
provider_slug: terminal-3
slug: terminal-3-eligibility
source_date: '2026-11-10'
source_filename: terminal-3-eligibility.yml
source_heading: Eligibility
source_page: https://terminal3.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Terminal 3\naid: terminal-3\nurl: https://terminal3.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided through the Services is not intended for distribution to, or use by, any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and must have reached the age of majority in the jurisdiction in which\n    you reside\n- type: business\n  text: where you act on behalf of another person or an entity,\
  \ that you have the authority to bind that person\n    or entity.\nrestricted_uses:\n- summary: Unlawful use\n  text: use the Services for any unlawful purpose or in any manner inconsistent with applicable law or regulation\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Verification of your identity may be performed by independent third-party providers\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and must have reached the age of majority in the jurisdiction in which\n    you reside\n"
source_yaml_url: https://artifacts.apis.io/terminal-3/eligibility/terminal-3-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Terminal 3's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity
- Decentralized Identity
- Verifiable Credentials
- OpenID Connect
- KYC
- AML
- Confidential Computing
- AI Agents
- Privacy
- Web3
- DID
---
