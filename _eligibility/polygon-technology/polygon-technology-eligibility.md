---
api_specs:
- filename: polygon-technology-auth-api-openapi.yml
  format: yaml
  label: Polygon Labs Auth API
  slug: polygon-technology-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-auth-api-openapi.yml
- filename: polygon-technology-cash-ins-api-openapi.yml
  format: yaml
  label: Polygon Labs Cash Ins API
  slug: polygon-technology-cash-ins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-cash-ins-api-openapi.yml
- filename: polygon-technology-counterparties-api-openapi.yml
  format: yaml
  label: Polygon Labs Counterparties API
  slug: polygon-technology-counterparties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-counterparties-api-openapi.yml
- filename: polygon-technology-customers-api-openapi.yml
  format: yaml
  label: Polygon Labs Customers API
  slug: polygon-technology-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-customers-api-openapi.yml
- filename: polygon-technology-deposit-addresses-api-openapi.yml
  format: yaml
  label: Polygon Labs Deposit Addresses API
  slug: polygon-technology-deposit-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-deposit-addresses-api-openapi.yml
- filename: polygon-technology-external-accounts-api-openapi.yml
  format: yaml
  label: Polygon Labs External Accounts API
  slug: polygon-technology-external-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-external-accounts-api-openapi.yml
- filename: polygon-technology-net-info-api-openapi.yml
  format: yaml
  label: Polygon Labs Net Info API
  slug: polygon-technology-net-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-net-info-api-openapi.yml
- filename: polygon-technology-networks-api-openapi.yml
  format: yaml
  label: Polygon Labs Networks API
  slug: polygon-technology-networks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-networks-api-openapi.yml
- filename: polygon-technology-polygon-labs-api-api-openapi.yml
  format: yaml
  label: Polygon Labs Polygon Labs API
  slug: polygon-technology-polygon-labs-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-polygon-labs-api-api-openapi.yml
- filename: polygon-technology-quotes-api-openapi.yml
  format: yaml
  label: Polygon Labs Quotes API
  slug: polygon-technology-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-quotes-api-openapi.yml
- filename: polygon-technology-status-api-openapi.yml
  format: yaml
  label: Polygon Labs Status API
  slug: polygon-technology-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-status-api-openapi.yml
- filename: polygon-technology-transactions-api-openapi.yml
  format: yaml
  label: Polygon Labs Transactions API
  slug: polygon-technology-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-transactions-api-openapi.yml
- filename: polygon-technology-virtual-accounts-api-openapi.yml
  format: yaml
  label: Polygon Labs Virtual Accounts API
  slug: polygon-technology-virtual-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-virtual-accounts-api-openapi.yml
- filename: polygon-technology-wallets-api-openapi.yml
  format: yaml
  label: Polygon Labs Wallets API
  slug: polygon-technology-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-wallets-api-openapi.yml
- filename: polygon-technology-webhooks-api-openapi.yml
  format: yaml
  label: Polygon Labs Webhooks API
  slug: polygon-technology-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polygon-technology/openapi/polygon-technology-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: the Interfaces or Features are not available to persons subject to sanctions or domiciled in a country or territory in which sanctions apply, as stated by the user representation (no countries named).
  entity_types:
  - text: The Interfaces and Features are intended only for users who are 18 years of age or older.
    type: individual
  - text: If you are entering into the Terms on behalf of an entity, such as the company you work for, you represent to us that you have the legal authority to bind such an entity.
    type: business
  minimum_age:
    text: The Interfaces and Features are intended only for users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties
    text: You represent and warrant that you are not, and for the duration of the time you use the Interfaces and Features, will not be (i) the subject of economic or trade sanctions administered or enforced by any governmental authority
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
name: Polygon Labs
provenance_date: '2026-11-10'
provider_name: Polygon Labs
provider_slug: polygon-technology
slug: polygon-technology-eligibility
source_date: '2026-11-10'
source_filename: polygon-technology-eligibility.yml
source_heading: Eligibility
source_page: https://polygon.technology/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Polygon Labs\naid: polygon-technology\nurl: https://polygon.technology/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: the Interfaces or Features are not available to persons subject to sanctions or domiciled in a country or\n    territory in which sanctions apply, as stated by the user representation (no countries named).\nentity_types:\n- type: individual\n  text: The Interfaces and Features are intended only for users who are 18 years of age or older.\n- type: business\n  text: If you are entering into the Terms on behalf of an entity, such as the company you work\
  \ for, you represent\n    to us that you have the legal authority to bind such an entity.\nrestricted_uses:\n- summary: Sanctioned parties\n  text: You represent and warrant that you are not, and for the duration of the time you use the Interfaces and\n    Features, will not be (i) the subject of economic or trade sanctions administered or enforced by any governmental\n    authority\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Interfaces and Features are intended only for users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/polygon-technology/eligibility/polygon-technology-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Polygon Labs's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Payments
- Blockchain
- Stablecoins
- Developer Platform
---
