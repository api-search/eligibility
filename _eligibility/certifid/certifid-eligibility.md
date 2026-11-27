---
api_specs:
- filename: certifid-accountverifications-api-openapi.yml
  format: yaml
  label: CertifID Account Verifications API
  slug: certifid-accountverifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-accountverifications-api-openapi.yml
- filename: certifid-banklookup-api-openapi.yml
  format: yaml
  label: CertifID Bank Lookup API
  slug: certifid-banklookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-banklookup-api-openapi.yml
- filename: certifid-collectrequest-api-openapi.yml
  format: yaml
  label: CertifID Collect Request API
  slug: certifid-collectrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-collectrequest-api-openapi.yml
- filename: certifid-confirmrequest-api-openapi.yml
  format: yaml
  label: CertifID Confirm Request API
  slug: certifid-confirmrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-confirmrequest-api-openapi.yml
- filename: certifid-disbursements-api-openapi.yml
  format: yaml
  label: CertifID Disbursements API
  slug: certifid-disbursements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-disbursements-api-openapi.yml
- filename: certifid-identityrequest-api-openapi.yml
  format: yaml
  label: CertifID Identity Request API
  slug: certifid-identityrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-identityrequest-api-openapi.yml
- filename: certifid-integration-api-openapi.yml
  format: yaml
  label: CertifID Integration API
  slug: certifid-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-integration-api-openapi.yml
- filename: certifid-lenders-api-openapi.yml
  format: yaml
  label: CertifID Lenders API
  slug: certifid-lenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-lenders-api-openapi.yml
- filename: certifid-location-api-openapi.yml
  format: yaml
  label: CertifID Location API
  slug: certifid-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-location-api-openapi.yml
- filename: certifid-payoffordering-api-openapi.yml
  format: yaml
  label: CertifID Payoff Ordering API
  slug: certifid-payoffordering-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-payoffordering-api-openapi.yml
- filename: certifid-sendrequest-api-openapi.yml
  format: yaml
  label: CertifID Send Request API
  slug: certifid-sendrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-sendrequest-api-openapi.yml
- filename: certifid-test-api-openapi.yml
  format: yaml
  label: CertifID Test API
  slug: certifid-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-test-api-openapi.yml
- filename: certifid-underwriter-api-openapi.yml
  format: yaml
  label: CertifID Underwriter API
  slug: certifid-underwriter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-underwriter-api-openapi.yml
- filename: certifid-users-api-openapi.yml
  format: yaml
  label: CertifID Users API
  slug: certifid-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-users-api-openapi.yml
- filename: certifid-wiringinstructions-api-openapi.yml
  format: yaml
  label: CertifID Wiring Instructions API
  slug: certifid-wiringinstructions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-wiringinstructions-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Company ... provides its Services, including the Website, for use only by persons located in the United States.
  entity_types:
  - text: Our Services, including the Website, are offered to and intended for users who are 18 years of age or older, and reside in the United States or any of its territories or possessions.
    type: individual
  - text: If you are not a consumer and you use the Payment Services to send or authorize a payment order that is not subject to the Electronic Fund Transfer Act, that transaction is governed by Article 4A of the Uniform Commercial Code
    type: business
  minimum_age:
    text: Our Services, including the Website, are offered to and intended for users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Financial crime
    text: Use the Services in connection with money laundering, terrorist financing, sanctions evasion, or any other financial crime.
  - summary: Impersonation
    text: To impersonate or attempt to impersonate the Company, a Company employee, another user, or any other person or entity
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
name: CertifID
provenance_date: '2026-11-09'
provider_name: CertifID
provider_slug: certifid
slug: certifid-eligibility
source_date: '2026-11-09'
source_filename: certifid-eligibility.yml
source_heading: Eligibility
source_page: https://www.certifid.com/company/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CertifID\naid: certifid\nurl: https://www.certifid.com/company/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Company ... provides its Services, including the Website, for use only by persons located in the United\n    States.\nentity_types:\n- type: individual\n  text: Our Services, including the Website, are offered to and intended for users who are 18 years of age or older,\n    and reside in the United States or any of its territories or possessions.\n- type: business\n  text: If you are not a consumer and you use the Payment Services\
  \ to send or authorize a payment order that is\n    not subject to the Electronic Fund Transfer Act, that transaction is governed by Article 4A of the Uniform Commercial\n    Code\nrestricted_uses:\n- summary: Financial crime\n  text: Use the Services in connection with money laundering, terrorist financing, sanctions evasion, or any other\n    financial crime.\n- summary: Impersonation\n  text: To impersonate or attempt to impersonate the Company, a Company employee, another user, or any other person\n    or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services, including the Website, are offered to and intended for users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/certifid/eligibility/certifid-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from CertifID's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wire Fraud Prevention
- Real Estate
- Title Insurance
- Identity Verification
- Business Verification
- Payments
- Fraud Prevention
- Escrow and Settlement
- Financial Services
- Security
---
