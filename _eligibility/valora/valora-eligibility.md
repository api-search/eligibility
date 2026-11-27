---
api_specs:
- filename: valora-hooks-api-openapi.yml
  format: yaml
  label: Valora Hooks API
  slug: valora-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valora/openapi/valora-hooks-api-openapi.yml
- filename: valora-swaps-api-openapi.yml
  format: yaml
  label: Valora Swaps API
  slug: valora-swaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valora/openapi/valora-swaps-api-openapi.yml
- filename: valora-tokens-api-openapi.yml
  format: yaml
  label: Valora Tokens API
  slug: valora-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valora/openapi/valora-tokens-api-openapi.yml
- filename: valora-transactions-api-openapi.yml
  format: yaml
  label: Valora Transactions API
  slug: valora-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valora/openapi/valora-transactions-api-openapi.yml
- filename: valora-nfts-api-openapi.yml
  format: yaml
  label: Valora Nfts API
  slug: valora-nfts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/valora/openapi/valora-nfts-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may only use Valora Services if permitted under the laws of your jurisdiction. Valora may refuse to let certain people/entities or devices access or use Valora Services
  entity_types:
  - text: You must be at least 18 years old and be able to form legally binding contracts to use Valora Services.
    type: individual
  - text: if you are accepting these Terms on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind such entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and be able to form legally binding contracts to use Valora Services.
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties and jurisdictions
    text: will not use, transfer, or provide access to Valora products or services to any sanctioned party or party located in a sanctioned jurisdiction
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
name: Valora
provenance_date: '2026-11-10'
provider_name: Valora
provider_slug: valora
slug: valora-eligibility
source_date: '2026-11-10'
source_filename: valora-eligibility.yml
source_heading: Eligibility
source_page: https://valora.xyz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Valora\naid: valora\nurl: https://valora.xyz/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may only use Valora Services if permitted under the laws of your jurisdiction. Valora may refuse to\n    let certain people/entities or devices access or use Valora Services\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and be able to form legally binding contracts to use Valora Services.\n- type: business\n  text: if you are accepting these Terms on behalf of a company or other legal entity, you represent and warrant\n    that you have the authority\
  \ to bind such entity to these Terms.\nrestricted_uses:\n- summary: Sanctioned parties and jurisdictions\n  text: will not use, transfer, or provide access to Valora products or services to any sanctioned party or party\n    located in a sanctioned jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and be able to form legally binding contracts to use Valora Services.\n"
source_yaml_url: https://artifacts.apis.io/valora/eligibility/valora-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Valora's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Wallets
- Payments
- DeFi
- Blockchain
- Celo
- Mobile
---
