---
api_specs:
- filename: aibidia-aibidia-tp-ai-api-api-openapi.yml
  format: yaml
  label: Aibidia Aibidia TP AI API
  slug: aibidia-aibidia-tp-ai-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aibidia/openapi/aibidia-aibidia-tp-ai-api-api-openapi.yml
- filename: aibidia-authorize-api-openapi.yml
  format: yaml
  label: Aibidia Authorize API
  slug: aibidia-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aibidia/openapi/aibidia-authorize-api-openapi.yml
- filename: aibidia-create-session-api-openapi.yml
  format: yaml
  label: Aibidia Create Session API
  slug: aibidia-create-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aibidia/openapi/aibidia-create-session-api-openapi.yml
- filename: aibidia-datainjections-api-openapi.yml
  format: yaml
  label: Aibidia Data Injections API
  slug: aibidia-datainjections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aibidia/openapi/aibidia-datainjections-api-openapi.yml
- filename: aibidia-extracttypes-api-openapi.yml
  format: yaml
  label: Aibidia Extract Types API
  slug: aibidia-extracttypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aibidia/openapi/aibidia-extracttypes-api-openapi.yml
- filename: aibidia-health-api-openapi.yml
  format: yaml
  label: Aibidia Health API
  slug: aibidia-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aibidia/openapi/aibidia-health-api-openapi.yml
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
  - summary: Compliance with laws
    text: The Customer shall not use the Aibidia Service in violation of applicable laws
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
name: Aibidia
provenance_date: '2026-11-09'
provider_name: Aibidia
provider_slug: aibidia
slug: aibidia-eligibility
source_date: '2026-11-09'
source_filename: aibidia-eligibility.yml
source_heading: Eligibility
source_page: https://www.aibidia.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aibidia\naid: aibidia\nurl: https://www.aibidia.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Compliance with laws\n  text: The Customer shall not use the Aibidia Service in violation of applicable laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aibidia/eligibility/aibidia-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Aibidia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transfer Pricing
- Tax Technology
- Tax Compliance
- Regulatory Reporting
- Country-by-Country Reporting
- Financial Data
- Enterprise Software
- Data Ingestion
- Finland
---
