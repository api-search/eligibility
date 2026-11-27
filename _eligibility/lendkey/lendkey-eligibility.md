---
api_specs:
- filename: lendkey-application-contracts-api-openapi.yml
  format: yaml
  label: LendKey Application Contracts API
  slug: lendkey-application-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-application-contracts-api-openapi.yml
- filename: lendkey-applications-api-openapi.yml
  format: yaml
  label: LendKey Applications API
  slug: lendkey-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-applications-api-openapi.yml
- filename: lendkey-auth-api-openapi.yml
  format: yaml
  label: LendKey Auth API
  slug: lendkey-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-auth-api-openapi.yml
- filename: lendkey-authentication-api-openapi.yml
  format: yaml
  label: LendKey Authentication API
  slug: lendkey-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-authentication-api-openapi.yml
- filename: lendkey-credit-risk-api-openapi.yml
  format: yaml
  label: LendKey Credit Risk API
  slug: lendkey-credit-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-credit-risk-api-openapi.yml
- filename: lendkey-disbursements-api-openapi.yml
  format: yaml
  label: LendKey Disbursements API
  slug: lendkey-disbursements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-disbursements-api-openapi.yml
- filename: lendkey-email-api-openapi.yml
  format: yaml
  label: LendKey Email API
  slug: lendkey-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-email-api-openapi.yml
- filename: lendkey-internal-api-openapi.yml
  format: yaml
  label: LendKey Internal API
  slug: lendkey-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-internal-api-openapi.yml
- filename: lendkey-leads-api-openapi.yml
  format: yaml
  label: LendKey Leads API
  slug: lendkey-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-leads-api-openapi.yml
- filename: lendkey-ledger-management-api-openapi.yml
  format: yaml
  label: LendKey Ledger Management API
  slug: lendkey-ledger-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-ledger-management-api-openapi.yml
- filename: lendkey-lender-templates-api-openapi.yml
  format: yaml
  label: LendKey Lender Templates API
  slug: lendkey-lender-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-lender-templates-api-openapi.yml
- filename: lendkey-loans-api-openapi.yml
  format: yaml
  label: LendKey Loans API
  slug: lendkey-loans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-loans-api-openapi.yml
- filename: lendkey-onboarding-api-openapi.yml
  format: yaml
  label: LendKey Onboarding API
  slug: lendkey-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-onboarding-api-openapi.yml
- filename: lendkey-payments-api-openapi.yml
  format: yaml
  label: LendKey Payments API
  slug: lendkey-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-payments-api-openapi.yml
- filename: lendkey-webhooks-api-openapi.yml
  format: yaml
  label: LendKey Webhooks API
  slug: lendkey-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lendkey/openapi/lendkey-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent that you are of legal age to enter into this legally binding Terms of Use with us.
    value: null
  restricted_uses:
  - summary: Unlawful or harmful user content
    text: 'You may not post on or transmit through the Website any data, text, music, sound, photographs, graphics, video, messages, or other material ("User Content") that: is defamatory, unlawful, harassing, abusive, threatening, obscene, hateful, sexist, or racially or ethnically offensive'
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
name: LendKey
provenance_date: '2026-11-09'
provider_name: LendKey
provider_slug: lendkey
slug: lendkey-eligibility
source_date: '2026-11-09'
source_filename: lendkey-eligibility.yml
source_heading: Eligibility
source_page: https://www.lendkey.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LendKey\naid: lendkey\nurl: https://www.lendkey.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful user content\n  text: 'You may not post on or transmit through the Website any data, text, music, sound, photographs, graphics,\n    video, messages, or other material (\"User Content\") that: is defamatory, unlawful, harassing, abusive, threatening,\n    obscene, hateful, sexist, or racially or ethnically offensive'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: You represent that you are of legal age to enter into this legally binding Terms of Use with us.\n"
source_yaml_url: https://artifacts.apis.io/lendkey/eligibility/lendkey-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from LendKey's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Loans
- Student Loans
- Credit Union
- Banking
- Loan Origination
- Financial Services
- Payments
- E-Signature
- Treasury
---
