---
api_specs:
- filename: afriex-balance-api-openapi.yml
  format: yaml
  label: Afriex Balance API
  slug: afriex-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afriex/openapi/afriex-balance-api-openapi.yml
- filename: afriex-checkout-sessions-api-openapi.yml
  format: yaml
  label: Afriex Checkout Sessions API
  slug: afriex-checkout-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afriex/openapi/afriex-checkout-sessions-api-openapi.yml
- filename: afriex-customers-api-openapi.yml
  format: yaml
  label: Afriex Customers API
  slug: afriex-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afriex/openapi/afriex-customers-api-openapi.yml
- filename: afriex-media-api-openapi.yml
  format: yaml
  label: Afriex Media API
  slug: afriex-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afriex/openapi/afriex-media-api-openapi.yml
- filename: afriex-payment-methods-api-openapi.yml
  format: yaml
  label: Afriex Payment Methods API
  slug: afriex-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afriex/openapi/afriex-payment-methods-api-openapi.yml
- filename: afriex-rates-api-openapi.yml
  format: yaml
  label: Afriex Rates API
  slug: afriex-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afriex/openapi/afriex-rates-api-openapi.yml
- filename: afriex-sme-registration-api-openapi.yml
  format: yaml
  label: Afriex SME Registration API
  slug: afriex-sme-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afriex/openapi/afriex-sme-registration-api-openapi.yml
- filename: afriex-transactions-api-openapi.yml
  format: yaml
  label: Afriex Transactions API
  slug: afriex-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afriex/openapi/afriex-transactions-api-openapi.yml
- filename: afriex-webhooks-api-openapi.yml
  format: yaml
  label: Afriex Webhooks API
  slug: afriex-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/afriex/openapi/afriex-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 3. a resident of a country in which we operate; and / or 4. a citizen of the United States.
  entity_types:
  - text: To use Afriex’ Website, or Services, you must be of legal age to form a binding contract with Afriex
    type: individual
  - text: Business accounts must be applied for and explicitly authorized.
    type: business
  minimum_age:
    text: at least 18 years of age
    value: null
  restricted_uses:
  - summary: Personal accounts not for business receipts
    text: Personal accounts may not be used to receive business, commercial or merchant transactions unless your occupation falls under the U.S. Department of Labor’s (“DOL”) definition of a Gig Worker
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: You hereby authorize the Company, directly or through third parties, to make any inquiries we consider necessary to validate your identity and / or authenticate your identity and account information and, for business accounts, your company or employer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Afriex
provenance_date: '2026-11-09'
provider_name: Afriex
provider_slug: afriex
slug: afriex-eligibility
source_date: '2026-11-09'
source_filename: afriex-eligibility.yml
source_heading: Eligibility
source_page: https://www.afriex.com/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Afriex\naid: afriex\nurl: https://www.afriex.com/terms-and-condition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 3. a resident of a country in which we operate; and / or 4. a citizen of the United States.\nentity_types:\n- type: individual\n  text: To use Afriex’ Website, or Services, you must be of legal age to form a binding contract with Afriex\n- type: business\n  text: Business accounts must be applied for and explicitly authorized.\nrestricted_uses:\n- summary: Personal accounts not for business receipts\n  text: Personal accounts may not be used to receive\
  \ business, commercial or merchant transactions unless your occupation\n    falls under the U.S. Department of Labor’s (“DOL”) definition of a Gig Worker\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: You hereby authorize the Company, directly or through third parties, to make any inquiries we consider necessary\n    to validate your identity and / or authenticate your identity and account information and, for business accounts,\n    your company or employer.\nminimum_age:\n  value: null\n  text: at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/afriex/eligibility/afriex-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Afriex's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Remittances
- Cross-Border Payments
- Fintech
- Financial Services
- Foreign Exchange
- Mobile Money
- Money Transfer
- Africa
- Stablecoins
- Virtual Accounts
- Webhook
- A2A
---
