---
api_specs:
- filename: merit-systems-balances-api-openapi.yml
  format: yaml
  label: Merit Systems Balances API
  slug: merit-systems-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merit-systems/openapi/merit-systems-balances-api-openapi.yml
- filename: merit-systems-invite-codes-api-openapi.yml
  format: yaml
  label: Merit Systems Invite Codes API
  slug: merit-systems-invite-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merit-systems/openapi/merit-systems-invite-codes-api-openapi.yml
- filename: merit-systems-organizations-api-openapi.yml
  format: yaml
  label: Merit Systems Organizations API
  slug: merit-systems-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merit-systems/openapi/merit-systems-organizations-api-openapi.yml
- filename: merit-systems-payments-api-openapi.yml
  format: yaml
  label: Merit Systems Payments API
  slug: merit-systems-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merit-systems/openapi/merit-systems-payments-api-openapi.yml
- filename: merit-systems-search-api-openapi.yml
  format: yaml
  label: Merit Systems Search API
  slug: merit-systems-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merit-systems/openapi/merit-systems-search-api-openapi.yml
- filename: merit-systems-send-api-openapi.yml
  format: yaml
  label: Merit Systems Send API
  slug: merit-systems-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/merit-systems/openapi/merit-systems-send-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in, organized in, or ordinarily resident in a jurisdiction where use of the Services would be prohibited
  entity_types:
  - text: you are at least 18 years old
    type: individual
  - text: If you use the Services on behalf of a company or other entity, you represent and warrant that you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Consumer reporting / FCRA-regulated decisions
    text: are not intended for use in connection with eligibility decisions regulated by the Fair Credit Reporting Act or analogous law
  - summary: High-risk use cases
    text: use the Services for emergency services, weapons, unlawful surveillance, or other prohibited high-risk use cases
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
name: Merit Systems
provenance_date: '2026-11-10'
provider_name: Merit Systems
provider_slug: merit-systems
slug: merit-systems-eligibility
source_date: '2026-11-10'
source_filename: merit-systems-eligibility.yml
source_heading: Eligibility
source_page: https://merit.systems/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Merit Systems\naid: merit-systems\nurl: https://merit.systems/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in, organized in, or ordinarily resident in a jurisdiction where use of the Services\n    would be prohibited\nentity_types:\n- type: individual\n  text: you are at least 18 years old\n- type: business\n  text: If you use the Services on behalf of a company or other entity, you represent and warrant that you have\n    authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Consumer reporting / FCRA-regulated decisions\n  text:\
  \ are not intended for use in connection with eligibility decisions regulated by the Fair Credit Reporting\n    Act or analogous law\n- summary: High-risk use cases\n  text: use the Services for emergency services, weapons, unlawful surveillance, or other prohibited high-risk use\n    cases\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/merit-systems/eligibility/merit-systems-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Merit Systems's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agentic Commerce
- Payments
- x402
- Micropayments
- MCP
- Stablecoins
- API Discovery
- Open Source
- Developer Tools
- Fintech
---
