---
api_specs:
- filename: accuracite-generate-api-openapi.yml
  format: yaml
  label: AccuraCite Generate API
  slug: accuracite-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accuracite/openapi/accuracite-generate-api-openapi.yml
- filename: accuracite-verify-api-openapi.yml
  format: yaml
  label: AccuraCite Verify API
  slug: accuracite-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accuracite/openapi/accuracite-verify-api-openapi.yml
- filename: accuracite-usage-api-openapi.yml
  format: yaml
  label: AccuraCite Usage API
  slug: accuracite-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accuracite/openapi/accuracite-usage-api-openapi.yml
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
  - summary: Unlawful or infringing content
    text: Not use the service for any unlawful purpose or to verify content that is illegal or infringes on others' rights.
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
name: AccuraCite
provenance_date: '2026-11-09'
provider_name: AccuraCite
provider_slug: accuracite
slug: accuracite-eligibility
source_date: '2026-11-09'
source_filename: accuracite-eligibility.yml
source_heading: Eligibility
source_page: https://accuracite.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AccuraCite\naid: accuracite\nurl: https://accuracite.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: Not use the service for any unlawful purpose or to verify content that is illegal or infringes on others'\n    rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accuracite/eligibility/accuracite-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from AccuraCite's own page on 2026-11-09.
synthetic: false
tags:
- Citations
- Research
- Bibliography
- Academic
- Verification
- AI Safety
---
