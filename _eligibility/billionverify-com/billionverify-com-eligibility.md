---
api_specs:
- filename: billionverify-com-account-api-openapi.yml
  format: yaml
  label: BillionVerify Account API
  slug: billionverify-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-account-api-openapi.yml
- filename: billionverify-com-file-processing-api-openapi.yml
  format: yaml
  label: BillionVerify File Processing API
  slug: billionverify-com-file-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-file-processing-api-openapi.yml
- filename: billionverify-com-health-api-openapi.yml
  format: yaml
  label: BillionVerify Health API
  slug: billionverify-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-health-api-openapi.yml
- filename: billionverify-com-verification-api-openapi.yml
  format: yaml
  label: BillionVerify Verification API
  slug: billionverify-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-verification-api-openapi.yml
- filename: billionverify-com-webhooks-api-openapi.yml
  format: yaml
  label: BillionVerify Webhooks API
  slug: billionverify-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billionverify-com/openapi/billionverify-com-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a contract to use the Service.
    type: individual
  - text: If you use the Service on behalf of a company or other entity, you represent that you are authorized to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: Violate anti-spam, privacy, consumer protection, or data protection laws.
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
name: BillionVerify
provenance_date: '2026-11-09'
provider_name: BillionVerify
provider_slug: billionverify-com
slug: billionverify-com-eligibility
source_date: '2026-11-09'
source_filename: billionverify-com-eligibility.yml
source_heading: Eligibility
source_page: https://billionverify.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BillionVerify\naid: billionverify-com\nurl: https://billionverify.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a contract to use the Service.\n- type: business\n  text: If you use the Service on behalf of a company or other entity, you represent that you are authorized to\n    bind that entity to these Terms.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: Violate anti-spam, privacy, consumer protection, or data protection laws.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/billionverify-com/eligibility/billionverify-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BillionVerify's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- Software-as-a-Service
- Data Quality
- B2B
---
