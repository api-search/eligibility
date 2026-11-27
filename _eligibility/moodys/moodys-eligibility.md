---
api_specs:
- filename: moodys-series-api-openapi.yml
  format: yaml
  label: Moody's Data Buffet API
  slug: data-buffet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-series-api-openapi.yml
- filename: moodys-audit-api-openapi.yml
  format: yaml
  label: Moody's Audit API
  slug: moodys-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-audit-api-openapi.yml
- filename: moodys-dataseries-api-openapi.yml
  format: yaml
  label: Moody's Data Series API
  slug: moodys-dataseries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-dataseries-api-openapi.yml
- filename: moodys-forecast-api-openapi.yml
  format: yaml
  label: Moody's Forecast API
  slug: moodys-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-forecast-api-openapi.yml
- filename: moodys-interpolation-api-openapi.yml
  format: yaml
  label: Moody's Interpolation API
  slug: moodys-interpolation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-interpolation-api-openapi.yml
- filename: moodys-order-api-openapi.yml
  format: yaml
  label: Moody's Order API
  slug: moodys-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-order-api-openapi.yml
- filename: moodys-project-api-openapi.yml
  format: yaml
  label: Moody's Project API
  slug: moodys-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-project-api-openapi.yml
- filename: moodys-scenario-api-openapi.yml
  format: yaml
  label: Moody's Scenario API
  slug: moodys-scenario-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-scenario-api-openapi.yml
- filename: moodys-seriessearch-api-openapi.yml
  format: yaml
  label: Moody's Series Search API
  slug: moodys-seriessearch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-seriessearch-api-openapi.yml
- filename: moodys-universe-api-openapi.yml
  format: yaml
  label: Moody's Universe API
  slug: moodys-universe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-universe-api-openapi.yml
- filename: moodys-vin-api-openapi.yml
  format: yaml
  label: Moody's Vin API
  slug: moodys-vin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-vin-api-openapi.yml
- filename: moodys-frequency-api-openapi.yml
  format: yaml
  label: Moody's Frequency API
  slug: moodys-frequency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-frequency-api-openapi.yml
- filename: moodys-multiseries-api-openapi.yml
  format: yaml
  label: Moody's Multi Series API
  slug: moodys-multiseries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-multiseries-api-openapi.yml
- filename: moodys-vintage-api-openapi.yml
  format: yaml
  label: Moody's Vintage API
  slug: moodys-vintage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-vintage-api-openapi.yml
- filename: moodys-file-types-api-openapi.yml
  format: yaml
  label: Moody's File Types API
  slug: moodys-file-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-file-types-api-openapi.yml
- filename: moodys-health-check-api-openapi.yml
  format: yaml
  label: Moody's Health Check API
  slug: moodys-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moodys/openapi/moodys-health-check-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    - RU
    served: []
    text: (currently Cuba, North Korea, Iran, Syria, and the Crimea, Donetsk, and Luhansk regions in Ukraine); (iii) located in Russia
  entity_types:
  - text: you or the entity on whose behalf you are accessing the Site
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Ratings not for retail investors
    text: ARE NOT INTENDED FOR USE BY RETAIL INVESTORS
  - summary: QIB information access
    text: you must be a QIB to access the QIB Information
  - summary: Not a regulatory benchmark
    text: NOT INTENDED FOR USE BY ANY PERSON AS A BENCHMARK
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- KP
- IR
- SY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Moody's
provenance_date: '2026-11-10'
provider_name: Moody's
provider_slug: moodys
slug: moodys-eligibility
source_date: '2026-11-10'
source_filename: moodys-eligibility.yml
source_heading: Eligibility
source_page: https://www.moodys.com/web/en/us/legal/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moody's\naid: moodys\nurl: https://www.moodys.com/web/en/us/legal/terms-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  - RU\n  text: (currently Cuba, North Korea, Iran, Syria, and the Crimea, Donetsk, and Luhansk regions in Ukraine); (iii)\n    located in Russia\nentity_types:\n- type: business\n  text: you or the entity on whose behalf you are accessing the Site\nrestricted_uses:\n- summary: Ratings not for retail investors\n  text: ARE NOT INTENDED FOR USE BY RETAIL INVESTORS\n- summary: QIB information access\n  text: you must be a QIB to access\
  \ the QIB Information\n- summary: Not a regulatory benchmark\n  text: NOT INTENDED FOR USE BY ANY PERSON AS A BENCHMARK\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moodys/eligibility/moodys-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Moody's's own page on 2026-11-10.
synthetic: false
tags:
- Climate Risk
- Compliance
- Credit Risk
- Economic Data
- Entity Verification
- Financial Analytics
- Insurance
- KYC
- Risk Management
- Screening
---
