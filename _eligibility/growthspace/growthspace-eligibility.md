---
api_specs:
- filename: growthspace-admin-api-openapi.yml
  format: yaml
  label: GrowthSpace Admin API
  slug: growthspace-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/growthspace/openapi/growthspace-admin-api-openapi.yml
- filename: growthspace-ah-api-openapi.yml
  format: yaml
  label: GrowthSpace Ah API
  slug: growthspace-ah-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/growthspace/openapi/growthspace-ah-api-openapi.yml
- filename: growthspace-growthspace-engineering-public-api-management-api-openapi.yml
  format: yaml
  label: GrowthSpace @growthspace Engineering/public Api Management API
  slug: growthspace-growthspace-engineering-public-api-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/growthspace/openapi/growthspace-growthspace-engineering-public-api-management-api-openapi.yml
- filename: growthspace-healthz-api-openapi.yml
  format: yaml
  label: GrowthSpace Healthz API
  slug: growthspace-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/growthspace/openapi/growthspace-healthz-api-openapi.yml
- filename: growthspace-public-api-openapi.yml
  format: yaml
  label: GrowthSpace Public API
  slug: growthspace-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/growthspace/openapi/growthspace-public-api-openapi.yml
- filename: growthspace-up-time-check-api-openapi.yml
  format: yaml
  label: GrowthSpace Up Time Check API
  slug: growthspace-up-time-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/growthspace/openapi/growthspace-up-time-check-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Customer shall ensure all Participants (including administrators and Internal Experts if applicable) are of minimum age of digital consent
    value: minimum age of digital consent
  restricted_uses:
  - summary: No high-risk employment decision-making with AI
    text: Customer shall not use any AI Functionalities for high-risk or regulated employment-related decision-making, including automated screening, ranking, selection, hiring, promotion, termination
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
name: GrowthSpace
provenance_date: '2026-11-09'
provider_name: GrowthSpace
provider_slug: growthspace
slug: growthspace-eligibility
source_date: '2026-11-09'
source_filename: growthspace-eligibility.yml
source_heading: Eligibility
source_page: https://www.growthspace.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GrowthSpace\naid: growthspace\nurl: https://www.growthspace.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No high-risk employment decision-making with AI\n  text: Customer shall not use any AI Functionalities for high-risk or regulated employment-related decision-making,\n    including automated screening, ranking, selection, hiring, promotion, termination\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: minimum age of digital consent\n  text: Customer shall ensure\
  \ all Participants (including administrators and Internal Experts if applicable) are\n    of minimum age of digital consent\n"
source_yaml_url: https://artifacts.apis.io/growthspace/eligibility/growthspace-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from GrowthSpace's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Learning and Development
- Talent Development
- Human Resources
- Coaching
- Employee Experience
- Skills
- Workforce
- Enterprise Software
- Artificial Intelligence
---
