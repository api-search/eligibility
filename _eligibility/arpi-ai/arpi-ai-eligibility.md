---
api_specs:
- filename: arpi-ai-authentication-api-openapi.yml
  format: yaml
  label: ARPI Inc. Authentication API
  slug: arpi-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arpi-ai/openapi/arpi-ai-authentication-api-openapi.yml
- filename: arpi-ai-diag-api-openapi.yml
  format: yaml
  label: ARPI Inc. Diag API
  slug: arpi-ai-diag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arpi-ai/openapi/arpi-ai-diag-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: EU/EEA Appendix applies to Users residing in the European Union or EEA. Users must be licensed medical professionals authorized in the country where the Application is used.
  entity_types:
  - text: Individuals who are not medical professionals cannot use the application.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No clinical use for RUO
    text: When using for research purposes, the results must never be used for a patient's diagnosis, treatment, prevention, or any other clinical purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Company permits use based on the User's qualification declaration and does not bear the obligation to directly verify the truthfulness of the content declared by the User.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ARPI Inc.
provenance_date: '2026-11-09'
provider_name: ARPI Inc.
provider_slug: arpi-ai
slug: arpi-ai-eligibility
source_date: '2026-11-09'
source_filename: arpi-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.arpi.ai/en/terms/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ARPI Inc.\naid: arpi-ai\nurl: https://www.arpi.ai/en/terms/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: EU/EEA Appendix applies to Users residing in the European Union or EEA. Users must be licensed medical professionals\n    authorized in the country where the Application is used.\nentity_types:\n- type: individual\n  text: Individuals who are not medical professionals cannot use the application.\nrestricted_uses:\n- summary: No clinical use for RUO\n  text: When using for research purposes, the results must never be used for a patient's diagnosis,\
  \ treatment, prevention,\n    or any other clinical purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Company permits use based on the User's qualification declaration and does not bear the obligation to\n    directly verify the truthfulness of the content declared by the User.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arpi-ai/eligibility/arpi-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from ARPI Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Medical AI
- Healthcare
- ECG
- Diagnostics
- Artificial Intelligence
---
