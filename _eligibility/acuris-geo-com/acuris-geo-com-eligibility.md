---
api_specs:
- filename: acuris-geo-com-account-api-openapi.yml
  format: yaml
  label: acuris-geo-com Account API
  slug: acuris-geo-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-account-api-openapi.yml
- filename: acuris-geo-com-billing-api-openapi.yml
  format: yaml
  label: acuris-geo-com Billing API
  slug: acuris-geo-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-billing-api-openapi.yml
- filename: acuris-geo-com-config-api-openapi.yml
  format: yaml
  label: acuris-geo-com Config API
  slug: acuris-geo-com-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-config-api-openapi.yml
- filename: acuris-geo-com-geocoding-api-openapi.yml
  format: yaml
  label: acuris-geo-com Geocoding API
  slug: acuris-geo-com-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-geocoding-api-openapi.yml
- filename: acuris-geo-com-postcode-lookup-api-openapi.yml
  format: yaml
  label: acuris-geo-com Postcode lookup API
  slug: acuris-geo-com-postcode-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-postcode-lookup-api-openapi.yml
- filename: acuris-geo-com-suggest-api-openapi.yml
  format: yaml
  label: acuris-geo-com Suggest API
  slug: acuris-geo-com-suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-suggest-api-openapi.yml
- filename: acuris-geo-com-validation-api-openapi.yml
  format: yaml
  label: acuris-geo-com Validation API
  slug: acuris-geo-com-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-validation-api-openapi.yml
- filename: acuris-geo-com-versioned-aliases-v1-api-openapi.yml
  format: yaml
  label: acuris-geo-com Versioned aliases (v1) API
  slug: acuris-geo-com-versioned-aliases-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acuris-geo-com/openapi/acuris-geo-com-versioned-aliases-v1-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Standalone resale of service
    text: You may not offer the API or Output Data as a standalone address validation, geocoding or autocomplete service
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
name: acuris-geo-com
provenance_date: '2026-11-09'
provider_name: acuris-geo-com
provider_slug: acuris-geo-com
slug: acuris-geo-com-eligibility
source_date: '2026-11-09'
source_filename: acuris-geo-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.acuris-geo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: acuris-geo-com\naid: acuris-geo-com\nurl: https://www.acuris-geo.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Standalone resale of service\n  text: You may not offer the API or Output Data as a standalone address validation, geocoding or autocomplete service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acuris-geo-com/eligibility/acuris-geo-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from acuris-geo-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Geocoding
- Address Validation
- Location Data
---
