---
api_specs:
- filename: credilinqai-authentication-api-openapi.yml
  format: yaml
  label: Credilinq.ai Authentication API
  slug: credilinqai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credilinqai/openapi/credilinqai-authentication-api-openapi.yml
- filename: credilinqai-customers-api-openapi.yml
  format: yaml
  label: Credilinq.ai Customers API
  slug: credilinqai-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credilinqai/openapi/credilinqai-customers-api-openapi.yml
- filename: credilinqai-kyc-api-openapi.yml
  format: yaml
  label: Credilinq.ai KYC API
  slug: credilinqai-kyc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credilinqai/openapi/credilinqai-kyc-api-openapi.yml
- filename: credilinqai-loans-api-openapi.yml
  format: yaml
  label: Credilinq.ai Loans API
  slug: credilinqai-loans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credilinqai/openapi/credilinqai-loans-api-openapi.yml
- filename: credilinqai-miscellaneous-api-openapi.yml
  format: yaml
  label: Credilinq.ai Miscellaneous API
  slug: credilinqai-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credilinqai/openapi/credilinqai-miscellaneous-api-openapi.yml
- filename: credilinqai-onboarding-api-openapi.yml
  format: yaml
  label: Credilinq.ai Onboarding API
  slug: credilinqai-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credilinqai/openapi/credilinqai-onboarding-api-openapi.yml
- filename: credilinqai-payment-api-openapi.yml
  format: yaml
  label: Credilinq.ai Payment API
  slug: credilinqai-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credilinqai/openapi/credilinqai-payment-api-openapi.yml
- filename: credilinqai-report-api-openapi.yml
  format: yaml
  label: Credilinq.ai Report API
  slug: credilinqai-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/credilinqai/openapi/credilinqai-report-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We may limit access to the Sites, Platform and/or services based on geography, user type, or other criteria.
  entity_types:
  - text: If you are acting on behalf of a business or legal entity, you confirm that you are authorized to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: Use the Sites, Platform and/or services for illegal or unauthorized purposes
  - summary: Automated data extraction
    text: Use automated tools to extract data
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
name: Credilinq.ai
provenance_date: '2026-11-09'
provider_name: Credilinq.ai
provider_slug: credilinqai
slug: credilinqai-eligibility
source_date: '2026-11-09'
source_filename: credilinqai-eligibility.yml
source_heading: Eligibility
source_page: https://credilinq.ai/termsandcondition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Credilinq.ai\naid: credilinqai\nurl: https://credilinq.ai/termsandcondition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We may limit access to the Sites, Platform and/or services based on geography, user type, or other criteria.\nentity_types:\n- type: business\n  text: If you are acting on behalf of a business or legal entity, you confirm that you are authorized to bind that\n    entity to these Terms.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Use the Sites, Platform and/or services for illegal or unauthorized purposes\n- summary: Automated data\
  \ extraction\n  text: Use automated tools to extract data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/credilinqai/eligibility/credilinqai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Credilinq.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Embedded Finance
- Lending
- Buy Now Pay Later
- Credit
- Payments
- KYC
- B2B
---
