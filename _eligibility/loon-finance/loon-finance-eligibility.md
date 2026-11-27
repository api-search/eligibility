---
api_specs:
- filename: loon-finance-attestations-api-openapi.yml
  format: yaml
  label: Loon Finance Attestations API
  slug: loon-finance-attestations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loon-finance/openapi/loon-finance-attestations-api-openapi.yml
- filename: loon-finance-issuances-api-openapi.yml
  format: yaml
  label: Loon Finance Issuances API
  slug: loon-finance-issuances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loon-finance/openapi/loon-finance-issuances-api-openapi.yml
- filename: loon-finance-supply-api-openapi.yml
  format: yaml
  label: Loon Finance Supply API
  slug: loon-finance-supply-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loon-finance/openapi/loon-finance-supply-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: Authorized Participant Accounts, CADC Services and support for CADC is currently only available to parties located in jurisdictions not subject to Canadian sanctions.
  minimum_age:
    text: You are at least 18 years old and have reached the age of majority required to use the CADC Services in the jurisdiction
    value: '18'
  restricted_uses:
  - summary: Prohibited transactions
    text: Operating as an unlicensed money transmitter, money service, payment service provider, e-money, or any other financial services business which requires licensure
  - summary: Gambling
    text: Gambling, except where permitted by law
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: We have engaged a third-party service provider to assist in verifying your identification information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Loon Finance
provenance_date: '2026-11-09'
provider_name: Loon Finance
provider_slug: loon-finance
slug: loon-finance-eligibility
source_date: '2026-11-09'
source_filename: loon-finance-eligibility.yml
source_heading: Eligibility
source_page: https://loon.finance/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loon Finance\naid: loon-finance\nurl: https://loon.finance/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: Authorized Participant Accounts, CADC Services and support for CADC is currently only available to parties\n    located in jurisdictions not subject to Canadian sanctions.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited transactions\n  text: Operating as an unlicensed money transmitter, money service, payment service provider, e-money, or any other\n    financial services business which requires licensure\n- summary: Gambling\n  text: Gambling,\
  \ except where permitted by law\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: We have engaged a third-party service provider to assist in verifying your identification information.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old and have reached the age of majority required to use the CADC Services in\n    the jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/loon-finance/eligibility/loon-finance-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Loon Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Stablecoins
- Cryptocurrency
- Payments
- Canada
- Digital Dollar
- Blockchain
- Transparency
- Stablecoin Issuance
---
