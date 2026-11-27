---
api_specs:
- filename: langbly-com-translation-api-openapi.yml
  format: yaml
  label: langbly-com Translation API
  slug: langbly-com-translation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/langbly-com/openapi/langbly-com-translation-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years old or have parental consent
    type: individual
  minimum_age:
    text: Be at least 18 years old or have parental consent
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Translate content that is illegal, harmful, or infringes on others' rights
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Use an authorized API key or approve a supported OAuth connection
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: langbly-com
provenance_date: '2026-11-09'
provider_name: langbly-com
provider_slug: langbly-com
slug: langbly-com-eligibility
source_date: '2026-11-09'
source_filename: langbly-com-eligibility.yml
source_heading: Eligibility
source_page: https://langbly.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: langbly-com\naid: langbly-com\nurl: https://langbly.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years old or have parental consent\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Translate content that is illegal, harmful, or infringes on others' rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Use an authorized API key or approve a supported OAuth connection\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old or have parental consent\n"
source_yaml_url: https://artifacts.apis.io/langbly-com/eligibility/langbly-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from langbly-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Translation
- Localization
- Software-as-a-Service
- Machine Learning
---
