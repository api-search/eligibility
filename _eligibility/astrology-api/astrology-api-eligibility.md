---
api_specs:
- filename: astrology-api-astrocartography-api-openapi.yml
  format: yaml
  label: Astrology API Astrocartography API
  slug: astrology-api-astrocartography-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-astrocartography-api-openapi.yml
- filename: astrology-api-face-reading-api-openapi.yml
  format: yaml
  label: Astrology API Face Reading API
  slug: astrology-api-face-reading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-face-reading-api-openapi.yml
- filename: astrology-api-human-design-api-openapi.yml
  format: yaml
  label: Astrology API Human Design API
  slug: astrology-api-human-design-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-human-design-api-openapi.yml
- filename: astrology-api-palm-reading-api-openapi.yml
  format: yaml
  label: Astrology API Palm Reading API
  slug: astrology-api-palm-reading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-palm-reading-api-openapi.yml
- filename: astrology-api-palmistry-service-api-api-openapi.yml
  format: yaml
  label: Astrology API Palmistry Service API
  slug: astrology-api-palmistry-service-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-palmistry-service-api-api-openapi.yml
- filename: astrology-api-pdf-reports-api-openapi.yml
  format: yaml
  label: Astrology API PDF Reports API
  slug: astrology-api-pdf-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-pdf-reports-api-openapi.yml
- filename: astrology-api-prediction-api-openapi.yml
  format: yaml
  label: Astrology API Prediction API
  slug: astrology-api-prediction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-prediction-api-openapi.yml
- filename: astrology-api-vedic-astrology-api-openapi.yml
  format: yaml
  label: Astrology API Vedic Astrology API
  slug: astrology-api-vedic-astrology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-vedic-astrology-api-openapi.yml
- filename: astrology-api-western-astrology-api-openapi.yml
  format: yaml
  label: Astrology API Western Astrology API
  slug: astrology-api-western-astrology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-western-astrology-api-openapi.yml
- filename: astrology-api-compatibility-api-openapi.yml
  format: yaml
  label: Astrology API Compatibility API
  slug: astrology-api-compatibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-compatibility-api-openapi.yml
- filename: astrology-api-compatibility-report-api-openapi.yml
  format: yaml
  label: Astrology API Compatibility Report API
  slug: astrology-api-compatibility-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-compatibility-report-api-openapi.yml
- filename: astrology-api-palm-query-api-openapi.yml
  format: yaml
  label: Astrology API Palm Query API
  slug: astrology-api-palm-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-palm-query-api-openapi.yml
- filename: astrology-api-palm-report-api-openapi.yml
  format: yaml
  label: Astrology API Palm Report API
  slug: astrology-api-palm-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-palm-report-api-openapi.yml
- filename: astrology-api-report-status-api-openapi.yml
  format: yaml
  label: Astrology API Report Status API
  slug: astrology-api-report-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astrology-api/openapi/astrology-api-report-status-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must provide your legal full name, a valid email address, and any other information requested in order to complete the signup process.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: You may not use the Services for any illegal or unauthorized purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must be a human. Accounts registered by "bots" or other automated methods are not permitted.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Astrology API
provenance_date: '2026-11-09'
provider_name: Astrology API
provider_slug: astrology-api
slug: astrology-api-eligibility
source_date: '2026-11-09'
source_filename: astrology-api-eligibility.yml
source_heading: Eligibility
source_page: https://astrologyapi.com/legal/terms-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astrology API\naid: astrology-api\nurl: https://astrologyapi.com/legal/terms-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must provide your legal full name, a valid email address, and any other information requested in order\n    to complete the signup process.\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: You may not use the Services for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must be a human. Accounts registered by\
  \ \"bots\" or other automated methods are not permitted.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/astrology-api/eligibility/astrology-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Astrology API's own page on 2026-11-09.
synthetic: false
tags:
- Astrology
- Horoscopes
- Zodiac
- Vedic Astrology
- Western Astrology
- Kundli
- Panchang
- Numerology
- Tarot
- Palmistry
- Human Design
- Astrocartography
- PDF Reports
- MCP
- Ephemeris
---
