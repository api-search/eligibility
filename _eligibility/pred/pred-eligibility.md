---
api_specs:
- filename: pred-authentication-api-openapi.yml
  format: yaml
  label: Pred Authentication API
  slug: pred-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-authentication-api-openapi.yml
- filename: pred-market-discovery-api-openapi.yml
  format: yaml
  label: Pred Market Discovery API
  slug: pred-market-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-market-discovery-api-openapi.yml
- filename: pred-orders-api-openapi.yml
  format: yaml
  label: Pred Orders API
  slug: pred-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-orders-api-openapi.yml
- filename: pred-overview-api-openapi.yml
  format: yaml
  label: Pred Overview API
  slug: pred-overview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-overview-api-openapi.yml
- filename: pred-portfolio-api-openapi.yml
  format: yaml
  label: Pred Portfolio API
  slug: pred-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-portfolio-api-openapi.yml
- filename: pred-user-api-openapi.yml
  format: yaml
  label: Pred User API
  slug: pred-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-user-api-openapi.yml
- filename: pred-websocket-api-openapi.yml
  format: yaml
  label: Pred WebSocket API
  slug: pred-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pred/openapi/pred-websocket-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    - GB
    - FR
    - CA
    - SG
    - PL
    - TH
    - TW
    - IR
    - SY
    - CU
    - KP
    served: []
    text: Restricted Jurisdictions include the United States, United Kingdom, France, Ontario, Singapore, Poland, Thailand, or Taiwan, and jurisdictions subject to comprehensive US sanctions including Iran, Syria, Cuba, North Korea, and the Crimea, Dontesk and Luhansk regions of Ukraine.
  entity_types:
  - text: If you are accepting these Terms on behalf of a company or other legal entity, you represent and warrant that you possess the requisite full legal authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: Access to the App is strictly limited to individuals who are at least eighteen (18) years old, or have attained the minimum age of majority required
    value: '18'
  restricted_uses:
  - summary: Restricted persons transacting Information Contracts
    text: ACCESS TO AND USE OF THE PLATFORM AND THE TECHNOLOGY FEATURES FOR TRANSACTING INFORMATION CONTRACTS IS STRICTLY PROHIBITED FOR ANY PERSON OR ENTITY WHO IS A RESTRICTED PERSON
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
- GB
- FR
- CA
- SG
- PL
- TH
- TW
- IR
- SY
- CU
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pred
provenance_date: '2026-11-10'
provider_name: Pred
provider_slug: pred
slug: pred-eligibility
source_date: '2026-11-10'
source_filename: pred-eligibility.yml
source_heading: Eligibility
source_page: https://www.pred.app/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pred\naid: pred\nurl: https://www.pred.app/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  - GB\n  - FR\n  - CA\n  - SG\n  - PL\n  - TH\n  - TW\n  - IR\n  - SY\n  - CU\n  - KP\n  text: Restricted Jurisdictions include the United States, United Kingdom, France, Ontario, Singapore, Poland,\n    Thailand, or Taiwan, and jurisdictions subject to comprehensive US sanctions including Iran, Syria, Cuba, North\n    Korea, and the Crimea, Dontesk and Luhansk regions of Ukraine.\nentity_types:\n- type: business\n  text: If you are accepting these Terms on behalf\
  \ of a company or other legal entity, you represent and warrant\n    that you possess the requisite full legal authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Restricted persons transacting Information Contracts\n  text: ACCESS TO AND USE OF THE PLATFORM AND THE TECHNOLOGY FEATURES FOR TRANSACTING INFORMATION CONTRACTS IS STRICTLY\n    PROHIBITED FOR ANY PERSON OR ENTITY WHO IS A RESTRICTED PERSON\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Access to the App is strictly limited to individuals who are at least eighteen (18) years old, or have attained\n    the minimum age of majority required\n"
source_yaml_url: https://artifacts.apis.io/pred/eligibility/pred-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pred's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Prediction Markets
- Sports
- Trading
- Exchange
- Web3
- Blockchain
- Base
- USDC
- Real-Time
---
