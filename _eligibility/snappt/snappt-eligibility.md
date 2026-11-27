---
api_specs:
- filename: snappt-account-api-openapi.yml
  format: yaml
  label: Snappt Account API
  slug: snappt-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-account-api-openapi.yml
- filename: snappt-applicant-sessions-api-openapi.yml
  format: yaml
  label: Snappt Applicant Sessions API
  slug: snappt-applicant-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-applicant-sessions-api-openapi.yml
- filename: snappt-applicants-api-openapi.yml
  format: yaml
  label: Snappt Applicants API
  slug: snappt-applicants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-applicants-api-openapi.yml
- filename: snappt-id-verification-api-openapi.yml
  format: yaml
  label: Snappt ID Verification API
  slug: snappt-id-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-id-verification-api-openapi.yml
- filename: snappt-internal-idv-api-openapi.yml
  format: yaml
  label: Snappt Internal IDV API
  slug: snappt-internal-idv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-internal-idv-api-openapi.yml
- filename: snappt-properties-api-openapi.yml
  format: yaml
  label: Snappt Properties API
  slug: snappt-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-properties-api-openapi.yml
- filename: snappt-webhooks-api-openapi.yml
  format: yaml
  label: Snappt Webhooks API
  slug: snappt-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappt/openapi/snappt-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are based in the United States and provided for access and use only by persons located in the United States.
  entity_types:
  - text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  - text: If you are a Client or accessing the Services on behalf of a Client, you further agree that you will only access and use the Services
    type: business
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: FCRA permissible purposes only for Clients
    text: you will only access and use the Services, and the information purveyed thereby, for
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
name: Snappt
provenance_date: '2026-11-10'
provider_name: Snappt
provider_slug: snappt
slug: snappt-eligibility
source_date: '2026-11-10'
source_filename: snappt-eligibility.yml
source_heading: Eligibility
source_page: https://snappt.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snappt\naid: snappt\nurl: https://snappt.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are based in the United States and provided for access and use only by persons located in the\n    United States.\nentity_types:\n- type: individual\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n- type: business\n  text: If you are a Client or accessing the Services on behalf of a Client, you further agree that you will only\n    access and use the Services\nrestricted_uses:\n- summary:\
  \ FCRA permissible purposes only for Clients\n  text: you will only access and use the Services, and the information purveyed thereby, for\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/snappt/eligibility/snappt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Snappt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fraud Prevention
- Document Verification
- Identity Verification
- Income Verification
- Property Management
- Multifamily
- Real Estate
- PropTech
- Tenant Screening
- Rental Applications
- Webhook
---
