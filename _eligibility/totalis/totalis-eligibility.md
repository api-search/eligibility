---
api_specs:
- filename: totalis-api-keys-api-openapi.yml
  format: yaml
  label: Totalis API Keys API
  slug: totalis-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/totalis/openapi/totalis-api-keys-api-openapi.yml
- filename: totalis-markets-api-openapi.yml
  format: yaml
  label: Totalis Markets API
  slug: totalis-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/totalis/openapi/totalis-markets-api-openapi.yml
- filename: totalis-portfolio-api-openapi.yml
  format: yaml
  label: Totalis Portfolio API
  slug: totalis-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/totalis/openapi/totalis-portfolio-api-openapi.yml
- filename: totalis-user-api-openapi.yml
  format: yaml
  label: Totalis User API
  slug: totalis-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/totalis/openapi/totalis-user-api-openapi.yml
- filename: totalis-vault-api-openapi.yml
  format: yaml
  label: Totalis Vault API
  slug: totalis-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/totalis/openapi/totalis-vault-api-openapi.yml
- filename: totalis-webhooks-api-openapi.yml
  format: yaml
  label: Totalis Webhooks API
  slug: totalis-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/totalis/openapi/totalis-webhooks-api-openapi.yml
- filename: totalis-rfqs-api-openapi.yml
  format: yaml
  label: Totalis RF Qs API
  slug: totalis-rfqs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/totalis/openapi/totalis-rfqs-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: you are not a U.S. Person, are not located in the United States, and are not accessing or using the Service from within the United States
  entity_types:
  - text: you are at least eighteen (18) years old or the age of legal majority in your jurisdiction, whichever is higher
    type: individual
  - text: If you access or use the Service on behalf of an entity or another person, you represent and warrant that you have all authority necessary to bind that entity or person to these Terms of Service
    type: business
  minimum_age:
    text: you are at least eighteen (18) years old or the age of legal majority in your jurisdiction, whichever is higher
    value: '18'
  restricted_uses:
  - summary: No use on behalf of U.S. Persons or restricted persons
    text: You may not access or use the Service on behalf of, for the benefit of, at the direction of, or in coordination with any U.S. Person or other restricted or ineligible person.
  - summary: Competitors barred from access
    text: No employee, independent contractor, agent, or affiliate of any competing company is permitted to view, access, or use any portion of the Service without express written permission from Totalis.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Totalis may require you to provide information or documentation regarding your identity, location, authority, source of funds, wallet ownership, eligibility, or compliance status at any time
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Totalis
provenance_date: '2026-11-10'
provider_name: Totalis
provider_slug: totalis
slug: totalis-eligibility
source_date: '2026-11-10'
source_filename: totalis-eligibility.yml
source_heading: Eligibility
source_page: https://docs.totalis.trade/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Totalis\naid: totalis\nurl: https://docs.totalis.trade/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  text: you are not a U.S. Person, are not located in the United States, and are not accessing or using the Service\n    from within the United States\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years old or the age of legal majority in your jurisdiction, whichever is\n    higher\n- type: business\n  text: If you access or use the Service on behalf of an entity or another person, you represent and warrant that\n   \
  \ you have all authority necessary to bind that entity or person to these Terms of Service\nrestricted_uses:\n- summary: No use on behalf of U.S. Persons or restricted persons\n  text: You may not access or use the Service on behalf of, for the benefit of, at the direction of, or in coordination\n    with any U.S. Person or other restricted or ineligible person.\n- summary: Competitors barred from access\n  text: No employee, independent contractor, agent, or affiliate of any competing company is permitted to view,\n    access, or use any portion of the Service without express written permission from Totalis.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Totalis may require you to provide information or documentation regarding your identity, location, authority,\n    source of funds, wallet ownership, eligibility, or compliance status at any time\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old or the age of legal majority in\
  \ your jurisdiction, whichever is\n    higher\n"
source_yaml_url: https://artifacts.apis.io/totalis/eligibility/totalis-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Totalis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Prediction Markets
- Derivatives
- Parlays
- Trading
- RFQ
- Solana
- Web3
- Market Data
- Webhook
- Real-Time
- Cryptocurrency
---
