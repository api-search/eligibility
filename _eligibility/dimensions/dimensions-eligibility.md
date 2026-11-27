---
api_specs:
- filename: dimensions-authentication-api-openapi.yml
  format: yaml
  label: Dimensions Authentication API
  slug: dimensions-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dimensions/openapi/dimensions-authentication-api-openapi.yml
- filename: dimensions-query-api-openapi.yml
  format: yaml
  label: Dimensions Query API
  slug: dimensions-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dimensions/openapi/dimensions-query-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you may not use Dimensions if not permitted by any export control or other applicable law, including because you are based in a sanctioned country or are on a sanctions list
  entity_types:
  - text: If you agree to these Terms as an individual, you must be at least 13 years old and otherwise of legal age to form a binding contract.
    type: individual
  minimum_age:
    text: If you agree to these Terms as an individual, you must be at least 13 years old
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: The Service is provided only for your own non-commercial, internal and personal use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company reserves the right to refuse registration of, or cancel a User ID in its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dimensions
provenance_date: '2026-11-09'
provider_name: Dimensions
provider_slug: dimensions
slug: dimensions-eligibility
source_date: '2026-11-09'
source_filename: dimensions-eligibility.yml
source_heading: Eligibility
source_page: https://www.dimensions.ai/website-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dimensions\naid: dimensions\nurl: https://www.dimensions.ai/website-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you may not use Dimensions if not permitted by any export control or other applicable law, including because\n    you are based in a sanctioned country or are on a sanctions list\nentity_types:\n- type: individual\n  text: If you agree to these Terms as an individual, you must be at least 13 years old and otherwise of legal age\n    to form a binding contract.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: The Service is provided only for your\
  \ own non-commercial, internal and personal use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Company reserves the right to refuse registration of, or cancel a User ID in its sole discretion.\nminimum_age:\n  value: '13'\n  text: If you agree to these Terms as an individual, you must be at least 13 years old\n"
source_yaml_url: https://artifacts.apis.io/dimensions/eligibility/dimensions-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Dimensions's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Research
- Publications
- Grants
- Patents
- Clinical Trials
- Jupyter Notebooks
- Scientometrics
- Bibliometrics
- Research Intelligence
- Datasets
- Policy Documents
- MCP
- Research Data
---
