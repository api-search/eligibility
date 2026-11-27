---
api_specs:
- filename: mobilevalidate-com-account-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Account API
  slug: mobilevalidate-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-account-api-openapi.yml
- filename: mobilevalidate-com-catalog-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Catalog API
  slug: mobilevalidate-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-catalog-api-openapi.yml
- filename: mobilevalidate-com-jobs-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Jobs API
  slug: mobilevalidate-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-jobs-api-openapi.yml
- filename: mobilevalidate-com-keys-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Keys API
  slug: mobilevalidate-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-keys-api-openapi.yml
- filename: mobilevalidate-com-lookup-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Lookup API
  slug: mobilevalidate-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-lookup-api-openapi.yml
- filename: mobilevalidate-com-system-api-openapi.yml
  format: yaml
  label: mobilevalidate-com System API
  slug: mobilevalidate-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-system-api-openapi.yml
- filename: mobilevalidate-com-webhooks-api-openapi.yml
  format: yaml
  label: mobilevalidate-com Webhooks API
  slug: mobilevalidate-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mobilevalidate-com/openapi/mobilevalidate-com-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Jurisdictions we do not serve are the countries and regions listed under Which countries are never checked? in our documentation. They include the occupied regions of Ukraine.
  entity_types:
  - text: The Service is offered only to businesses, public bodies and other organisations, and to sole traders acting in the course of their trade. Consumers may not use it.
    type: business
  minimum_age:
    text: The individual who accepts these Terms represents that they are at least 18 years old and authorised to bind the Customer.
    value: '18'
  restricted_uses:
  - summary: No eligibility decisions (FCRA)
    text: You will not use the Service or any Result as a factor in establishing eligibility for credit, insurance, employment, housing, tenancy or any other purpose covered by the US Fair Credit Reporting Act or similar laws
  - summary: No surveillance or identification
    text: You will not use the Service or the Results to stalk, harass, monitor, track or locate any person
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We approve accounts automatically, after screening against sanctions lists and the jurisdictions in section 13. We do not review your use case
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: mobilevalidate-com
provenance_date: '2026-11-10'
provider_name: mobilevalidate-com
provider_slug: mobilevalidate-com
slug: mobilevalidate-com-eligibility
source_date: '2026-11-10'
source_filename: mobilevalidate-com-eligibility.yml
source_heading: Eligibility
source_page: https://mobilevalidate.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mobilevalidate-com\naid: mobilevalidate-com\nurl: https://mobilevalidate.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Jurisdictions we do not serve are the countries and regions listed under Which countries are never checked?\n    in our documentation. They include the occupied regions of Ukraine.\nentity_types:\n- type: business\n  text: The Service is offered only to businesses, public bodies and other organisations, and to sole traders acting\n    in the course of their trade. Consumers may not use it.\nrestricted_uses:\n- summary: No eligibility decisions (FCRA)\n\
  \  text: You will not use the Service or any Result as a factor in establishing eligibility for credit, insurance,\n    employment, housing, tenancy or any other purpose covered by the US Fair Credit Reporting Act or similar laws\n- summary: No surveillance or identification\n  text: You will not use the Service or the Results to stalk, harass, monitor, track or locate any person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We approve accounts automatically, after screening against sanctions lists and the jurisdictions in section\n    13. We do not review your use case\nminimum_age:\n  value: '18'\n  text: The individual who accepts these Terms represents that they are at least 18 years old and authorised to\n    bind the Customer.\n"
source_yaml_url: https://artifacts.apis.io/mobilevalidate-com/eligibility/mobilevalidate-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from mobilevalidate-com's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- Phone Validation
- Email Verification
- API Service
- Telecommunications
---
