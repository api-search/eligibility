---
api_specs:
- filename: collegecalcai-com-chances-api-openapi.yml
  format: yaml
  label: CollegeCalcAI Chances API
  slug: collegecalcai-com-chances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collegecalcai-com/openapi/collegecalcai-com-chances-api-openapi.yml
- filename: collegecalcai-com-colleges-api-openapi.yml
  format: yaml
  label: CollegeCalcAI Colleges API
  slug: collegecalcai-com-colleges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collegecalcai-com/openapi/collegecalcai-com-colleges-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for users in the United States; if you use it from elsewhere, you are responsible for compliance with your local laws.
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you are under 18, you may use the Service only with the involvement and consent of a parent or legal guardian
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Misrepresenting student chances
    text: Do not use results from the Service to misrepresent a student's chances to any third party.
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
name: CollegeCalcAI
provenance_date: '2026-11-09'
provider_name: CollegeCalcAI
provider_slug: collegecalcai-com
slug: collegecalcai-com-eligibility
source_date: '2026-11-09'
source_filename: collegecalcai-com-eligibility.yml
source_heading: Eligibility
source_page: https://collegecalcai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CollegeCalcAI\naid: collegecalcai-com\nurl: https://collegecalcai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for users in the United States; if you use it from elsewhere, you are responsible\n    for compliance with your local laws.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you are under 18, you may use the Service only\n    with the involvement and consent of a parent or legal guardian\nrestricted_uses:\n- summary: Misrepresenting student chances\n  text: Do not use results from\
  \ the Service to misrepresent a student's chances to any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/collegecalcai-com/eligibility/collegecalcai-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CollegeCalcAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- College Admissions
- Higher Education
- Students
- Calculators
- MCP
- Artificial Intelligence
---
