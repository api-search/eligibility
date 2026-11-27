---
api_specs:
- filename: detectlanguage-account-api-openapi.yml
  format: yaml
  label: DetectLanguage Account API
  slug: detectlanguage-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/detectlanguage/openapi/detectlanguage-account-api-openapi.yml
- filename: detectlanguage-detection-api-openapi.yml
  format: yaml
  label: DetectLanguage Detection API
  slug: detectlanguage-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/detectlanguage/openapi/detectlanguage-detection-api-openapi.yml
- filename: detectlanguage-languages-api-openapi.yml
  format: yaml
  label: DetectLanguage Languages API
  slug: detectlanguage-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/detectlanguage/openapi/detectlanguage-languages-api-openapi.yml
claim_count: 2
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
  - summary: Prohibited product categories
    text: 'use the detectlanguage.com APIs in connection with or to promote any products, services, or materials that constitute, promote or are used primarily for the purpose of dealing in: spyware, adware, or other malicious programs or code'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate identification, contact, and other information required as part of the registration process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DetectLanguage
provenance_date: '2026-11-09'
provider_name: DetectLanguage
provider_slug: detectlanguage
slug: detectlanguage-eligibility
source_date: '2026-11-09'
source_filename: detectlanguage-eligibility.yml
source_heading: Eligibility
source_page: https://detectlanguage.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DetectLanguage\naid: detectlanguage\nurl: https://detectlanguage.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited product categories\n  text: 'use the detectlanguage.com APIs in connection with or to promote any products, services, or materials that\n    constitute, promote or are used primarily for the purpose of dealing in: spyware, adware, or other malicious\n    programs or code'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate identification, contact,\
  \ and other information required as part of the registration\n    process.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/detectlanguage/eligibility/detectlanguage-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from DetectLanguage's own page on 2026-11-09.
synthetic: false
tags:
- Language Detection
- Natural Language Processing
- Text Analysis
- Machine Learning
- Multilingual
---
