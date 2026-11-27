---
api_specs:
- filename: syndicate-api-key-manager-admin-api-openapi.yml
  format: yaml
  label: Syndicate api-key-manager > admin API
  slug: syndicate-api-key-manager-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syndicate/openapi/syndicate-api-key-manager-admin-api-openapi.yml
- filename: syndicate-call-api-openapi.yml
  format: yaml
  label: Syndicate Call API
  slug: syndicate-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syndicate/openapi/syndicate-call-api-openapi.yml
- filename: syndicate-transact-api-openapi.yml
  format: yaml
  label: Syndicate Transact API
  slug: syndicate-transact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syndicate/openapi/syndicate-transact-api-openapi.yml
- filename: syndicate-wallet-api-openapi.yml
  format: yaml
  label: Syndicate Wallet API
  slug: syndicate-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/syndicate/openapi/syndicate-wallet-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST EIGHTEEN (18) YEARS OLD.
    type: individual
  - text: If you are acting on behalf of a DAO or other entity, whether or not such entity is formally incorporated under the laws of your jurisdiction, you represent and warrant that you have all right and authority necessary to act on behalf of such entity.
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST EIGHTEEN (18) YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Sanctions and export restrictions
    text: Syndicate does not encourage, induce, or sanction the deployment, integration, or use of the Service in violation of applicable laws or regulations and hereby prohibits any such deployment, integration or use.
  - summary: No commercial/third-party use
    text: The Services are not intended to be used by you for or on behalf of any third party.
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
name: Syndicate
provenance_date: '2026-11-10'
provider_name: Syndicate
provider_slug: syndicate
slug: syndicate-eligibility
source_date: '2026-11-10'
source_filename: syndicate-eligibility.yml
source_heading: Eligibility
source_page: https://syndicate.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Syndicate\naid: syndicate\nurl: https://syndicate.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST EIGHTEEN (18) YEARS\n    OLD.\n- type: business\n  text: If you are acting on behalf of a DAO or other entity, whether or not such entity is formally incorporated\n    under the laws of your jurisdiction, you represent and warrant that you have all right and authority necessary\n    to act on behalf of such entity.\nrestricted_uses:\n\
  - summary: Sanctions and export restrictions\n  text: Syndicate does not encourage, induce, or sanction the deployment, integration, or use of the Service in\n    violation of applicable laws or regulations and hereby prohibits any such deployment, integration or use.\n- summary: No commercial/third-party use\n  text: The Services are not intended to be used by you for or on behalf of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THIS AGREEMENT IF YOU ARE NOT AT LEAST EIGHTEEN (18) YEARS\n    OLD.\n"
source_yaml_url: https://artifacts.apis.io/syndicate/eligibility/syndicate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Syndicate's own page on 2026-11-10.
synthetic: false
tags:
- Blockchain
- Web3
- Ethereum
- Transaction
- Wallets
- EVM
- Infrastructure
- Signing
- Webhook
- Cryptography
---
