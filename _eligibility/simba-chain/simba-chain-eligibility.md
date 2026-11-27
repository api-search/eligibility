---
api_specs:
- filename: simba-chain-authentication-api-openapi.yml
  format: yaml
  label: SIMBA Chain Authentication API
  slug: simba-chain-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-authentication-api-openapi.yml
- filename: simba-chain-bulk-users-import-requests-api-openapi.yml
  format: yaml
  label: SIMBA Chain Bulk Users Import Requests API
  slug: simba-chain-bulk-users-import-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-bulk-users-import-requests-api-openapi.yml
- filename: simba-chain-deviceappadmin-api-openapi.yml
  format: yaml
  label: SIMBA Chain Device App Admin API
  slug: simba-chain-deviceappadmin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-deviceappadmin-api-openapi.yml
- filename: simba-chain-deviceappregistration-api-openapi.yml
  format: yaml
  label: SIMBA Chain Device App Registration API
  slug: simba-chain-deviceappregistration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-deviceappregistration-api-openapi.yml
- filename: simba-chain-domains-api-openapi.yml
  format: yaml
  label: SIMBA Chain Domains API
  slug: simba-chain-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-domains-api-openapi.yml
- filename: simba-chain-events-api-openapi.yml
  format: yaml
  label: SIMBA Chain Events API
  slug: simba-chain-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-events-api-openapi.yml
- filename: simba-chain-invites-api-openapi.yml
  format: yaml
  label: SIMBA Chain Invites API
  slug: simba-chain-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-invites-api-openapi.yml
- filename: simba-chain-organisations-api-openapi.yml
  format: yaml
  label: SIMBA Chain Organisations API
  slug: simba-chain-organisations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-organisations-api-openapi.yml
- filename: simba-chain-passkeys-api-openapi.yml
  format: yaml
  label: SIMBA Chain Passkeys API
  slug: simba-chain-passkeys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-passkeys-api-openapi.yml
- filename: simba-chain-permissions-api-openapi.yml
  format: yaml
  label: SIMBA Chain Permissions API
  slug: simba-chain-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-permissions-api-openapi.yml
- filename: simba-chain-probes-api-openapi.yml
  format: yaml
  label: SIMBA Chain Probes API
  slug: simba-chain-probes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-probes-api-openapi.yml
- filename: simba-chain-roles-api-openapi.yml
  format: yaml
  label: SIMBA Chain Roles API
  slug: simba-chain-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-roles-api-openapi.yml
- filename: simba-chain-serviceadmin-api-openapi.yml
  format: yaml
  label: SIMBA Chain Service Admin API
  slug: simba-chain-serviceadmin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-serviceadmin-api-openapi.yml
- filename: simba-chain-templates-api-openapi.yml
  format: yaml
  label: SIMBA Chain Templates API
  slug: simba-chain-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-templates-api-openapi.yml
- filename: simba-chain-users-api-openapi.yml
  format: yaml
  label: SIMBA Chain Users API
  slug: simba-chain-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-users-api-openapi.yml
- filename: simba-chain-client-credentials-api-openapi.yml
  format: yaml
  label: SIMBA Chain Client Credentials API
  slug: simba-chain-client-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-client-credentials-api-openapi.yml
- filename: simba-chain-two-factor-api-openapi.yml
  format: yaml
  label: SIMBA Chain Two Factor API
  slug: simba-chain-two-factor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simba-chain/openapi/simba-chain-two-factor-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Product is intended for users who are at least 18 years of age.
    type: individual
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: Persons under the age of 18 are not permitted to use the Product.
    value: '18'
  restricted_uses:
  - summary: Harassment or harm
    text: Use the Product or its Output in order to harass, abuse, or harm another person.
  - summary: Unlawful use
    text: YOU WILL NOT USE THE PRODUCT FOR ANY ILLEGAL OR UNAUTHORIZED PURPOSE
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
name: SIMBA Chain
provenance_date: '2026-11-10'
provider_name: SIMBA Chain
provider_slug: simba-chain
slug: simba-chain-eligibility
source_date: '2026-11-10'
source_filename: simba-chain-eligibility.yml
source_heading: Eligibility
source_page: https://simbachain.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SIMBA Chain\naid: simba-chain\nurl: https://simbachain.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Product is intended for users who are at least 18 years of age.\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Harassment or harm\n  text: Use the Product or its Output in order to harass, abuse, or harm another person.\n- summary: Unlawful use\n  text: YOU WILL NOT USE THE PRODUCT FOR ANY ILLEGAL OR UNAUTHORIZED PURPOSE\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Persons under the age of 18 are not permitted to use the Product.\n"
source_yaml_url: https://artifacts.apis.io/simba-chain/eligibility/simba-chain-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SIMBA Chain's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Blockchain
- Supply Chain
- Traceability
- Digital Product Passport
- Smart Contracts
- Identity
- Verifiable Credentials
- Defense
- Government
- Data Management
---
