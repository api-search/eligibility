---
api_specs:
- filename: banzai-events-api-openapi.yml
  format: yaml
  label: Banzai Events API
  slug: banzai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/banzai/openapi/banzai-events-api-openapi.yml
- filename: banzai-intro-api-openapi.yml
  format: yaml
  label: Banzai Intro API
  slug: banzai-intro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/banzai/openapi/banzai-intro-api-openapi.yml
- filename: banzai-reports-api-openapi.yml
  format: yaml
  label: Banzai Reports API
  slug: banzai-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/banzai/openapi/banzai-reports-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: to use our Services, you must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Applicable law and export controls
    text: You may use our Services only as permitted by applicable law, including export control laws and regulations.
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
name: Banzai
provenance_date: '2026-11-09'
provider_name: Banzai
provider_slug: banzai
slug: banzai-eligibility
source_date: '2026-11-09'
source_filename: banzai-eligibility.yml
source_heading: Eligibility
source_page: https://www.banzai.io/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Banzai\naid: banzai\nurl: https://www.banzai.io/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Applicable law and export controls\n  text: You may use our Services only as permitted by applicable law, including export control laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: to use our Services, you must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/banzai/eligibility/banzai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Banzai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Marketing Technology
- Event Management
- Webinars
- Video
- Engagement Marketing
- Demand Generation
- Software-as-a-Service
---
