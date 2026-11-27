---
api_specs:
- filename: fipto-aisp-pisp-api-openapi.yml
  format: yaml
  label: Fipto AISP/PISP API
  slug: fipto-aisp-pisp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-aisp-pisp-api-openapi.yml
- filename: fipto-assets-api-openapi.yml
  format: yaml
  label: Fipto Assets API
  slug: fipto-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-assets-api-openapi.yml
- filename: fipto-automations-api-openapi.yml
  format: yaml
  label: Fipto Automations API
  slug: fipto-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-automations-api-openapi.yml
- filename: fipto-beneficiaries-api-openapi.yml
  format: yaml
  label: Fipto Beneficiaries API
  slug: fipto-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-beneficiaries-api-openapi.yml
- filename: fipto-companies-api-openapi.yml
  format: yaml
  label: Fipto Companies API
  slug: fipto-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-companies-api-openapi.yml
- filename: fipto-conversions-api-openapi.yml
  format: yaml
  label: Fipto Conversions API
  slug: fipto-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-conversions-api-openapi.yml
- filename: fipto-internal-transfers-api-openapi.yml
  format: yaml
  label: Fipto Internal Transfers API
  slug: fipto-internal-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-internal-transfers-api-openapi.yml
- filename: fipto-payin-simulation-api-openapi.yml
  format: yaml
  label: Fipto Payin Simulation API
  slug: fipto-payin-simulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-payin-simulation-api-openapi.yml
- filename: fipto-payment-links-api-openapi.yml
  format: yaml
  label: Fipto Payment links API
  slug: fipto-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-payment-links-api-openapi.yml
- filename: fipto-transactions-api-openapi.yml
  format: yaml
  label: Fipto Transactions API
  slug: fipto-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-transactions-api-openapi.yml
- filename: fipto-travel-rule-api-openapi.yml
  format: yaml
  label: Fipto Travel Rule API
  slug: fipto-travel-rule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-travel-rule-api-openapi.yml
- filename: fipto-wallets-api-openapi.yml
  format: yaml
  label: Fipto Wallets API
  slug: fipto-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-wallets-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Prohibited Jurisdictions refers to high-risk jurisdictions listed by the French, European and international authorities and Fipto. Company must act on behalf of a company with its registered office in a country which is accepted by Fipto.
  entity_types:
  - text: The Services enable companies and entrepreneurs operating as micro-enterprises and/or sole traders, limited liability companies, single-member limited liability companies, simplified joint stock companies, and single-member simplified joint stock companies to access Fipto's Services.
    type: business
  minimum_age:
    text: be of legal age
    value: null
  restricted_uses:
  - summary: Excluded business sectors
    text: 'Fipto accepts all sectors of industry and commerce with the exception of the following areas (non-exhaustive list subject to change): activities of cannabis, endangered animal species, nominee directors / shareholders services, shell companies / use of shell banks, adult content, companies with nominee directors / shareholders, prohibited drugs, opening accounts on behalf of clients, offshore company formation services, weapons, military or semi-military, precious stones and metals'
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
name: Fipto
provenance_date: '2026-11-09'
provider_name: Fipto
provider_slug: fipto
slug: fipto-eligibility
source_date: '2026-11-09'
source_filename: fipto-eligibility.yml
source_heading: Eligibility
source_page: https://www.fipto.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fipto\naid: fipto\nurl: https://www.fipto.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Prohibited Jurisdictions refers to high-risk jurisdictions listed by the French, European and international\n    authorities and Fipto. Company must act on behalf of a company with its registered office in a country which\n    is accepted by Fipto.\nentity_types:\n- type: business\n  text: The Services enable companies and entrepreneurs operating as micro-enterprises and/or sole traders, limited\n    liability companies, single-member limited\
  \ liability companies, simplified joint stock companies, and single-member\n    simplified joint stock companies to access Fipto's Services.\nrestricted_uses:\n- summary: Excluded business sectors\n  text: 'Fipto accepts all sectors of industry and commerce with the exception of the following areas (non-exhaustive\n    list subject to change): activities of cannabis, endangered animal species, nominee directors / shareholders\n    services, shell companies / use of shell banks, adult content, companies with nominee directors / shareholders,\n    prohibited drugs, opening accounts on behalf of clients, offshore company formation services, weapons, military\n    or semi-military, precious stones and metals'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: be of legal age\n"
source_yaml_url: https://artifacts.apis.io/fipto/eligibility/fipto-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fipto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blockchain
- Payments
- Stablecoins
- Banking
- Treasury
- Cross-Border Payments
- Digital Currency
- Fintech
- Wallets
---
