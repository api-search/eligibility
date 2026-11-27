---
api_specs:
- filename: abstract-api-vat-validation-api-openapi.yml
  format: yaml
  label: Abstract API VAT Validation API
  slug: abstract-api-vat-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-vat-validation-api-openapi.yml
- filename: abstract-api-abstract-avatars-api-api-openapi.yml
  format: yaml
  label: Abstract API Abstract Avatars API
  slug: abstract-api-abstract-avatars-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-abstract-avatars-api-api-openapi.yml
- filename: abstract-api-calculate-api-openapi.yml
  format: yaml
  label: Abstract API Calculate API
  slug: abstract-api-calculate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-calculate-api-openapi.yml
- filename: abstract-api-categories-api-openapi.yml
  format: yaml
  label: Abstract API Categories API
  slug: abstract-api-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-categories-api-openapi.yml
- filename: abstract-api-convert-api-openapi.yml
  format: yaml
  label: Abstract API Convert API
  slug: abstract-api-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-convert-api-openapi.yml
- filename: abstract-api-convert-time-api-openapi.yml
  format: yaml
  label: Abstract API Convert Time API
  slug: abstract-api-convert-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-convert-time-api-openapi.yml
- filename: abstract-api-current-time-api-openapi.yml
  format: yaml
  label: Abstract API Current Time API
  slug: abstract-api-current-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-current-time-api-openapi.yml
- filename: abstract-api-historical-api-openapi.yml
  format: yaml
  label: Abstract API Historical API
  slug: abstract-api-historical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-historical-api-openapi.yml
- filename: abstract-api-live-api-openapi.yml
  format: yaml
  label: Abstract API Live API
  slug: abstract-api-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-live-api-openapi.yml
- filename: abstract-api-upload-api-openapi.yml
  format: yaml
  label: Abstract API Upload API
  slug: abstract-api-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-upload-api-openapi.yml
- filename: abstract-api-url-api-openapi.yml
  format: yaml
  label: Abstract API URL API
  slug: abstract-api-url-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-url-api-openapi.yml
- filename: abstract-api-validate-api-openapi.yml
  format: yaml
  label: Abstract API Validate API
  slug: abstract-api-validate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abstract-api/openapi/abstract-api-validate-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register an account with the Site.
    value: '18'
  restricted_uses:
  - summary: HIPAA/FISMA/GLBA regulated interactions
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: Government intelligence and eligibility decisions
    text: to benefit any government agency operating as an intelligence agency whose purpose is to collect and analyze data on people
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Abstract API
provenance_date: '2026-11-09'
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-eligibility
source_date: '2026-11-09'
source_filename: abstract-api-eligibility.yml
source_heading: Eligibility
source_page: https://www.abstractapi.com/legal/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Abstract API\naid: abstract-api\nurl: https://www.abstractapi.com/legal/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: made between you, whether personally or on behalf of an entity\nrestricted_uses:\n- summary: HIPAA/FISMA/GLBA regulated interactions\n  text: The Site is not tailored to comply with industry-specific\
  \ regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: Government intelligence and eligibility decisions\n  text: to benefit any government agency operating as an intelligence agency whose purpose is to collect and analyze\n    data on people\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register an account with the Site.\n"
source_yaml_url: https://artifacts.apis.io/abstract-api/eligibility/abstract-api-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Abstract API's own page on 2026-11-09.
synthetic: false
tags:
- Avatars
- Company Enrichment
- Contacts
- Currency
- Email Verification
- Exchange Rates
- IBAN Validation
- Image Processing
- IP Geolocation
- IP Intelligence
- Phone Validation
- Public Holidays
- Screenshots
- Timezone
- VAT Validation
- Web Scraping
- A2A
- Data Enrichment
---
