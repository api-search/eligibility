---
api_specs:
- filename: wizehire-agent-api-openapi.yml
  format: yaml
  label: WizeHire Agent API
  slug: wizehire-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wizehire/openapi/wizehire-agent-api-openapi.yml
- filename: wizehire-candidates-api-openapi.yml
  format: yaml
  label: WizeHire Candidates API
  slug: wizehire-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wizehire/openapi/wizehire-candidates-api-openapi.yml
- filename: wizehire-health-api-openapi.yml
  format: yaml
  label: WizeHire Health API
  slug: wizehire-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wizehire/openapi/wizehire-health-api-openapi.yml
- filename: wizehire-interviews-api-openapi.yml
  format: yaml
  label: WizeHire Interviews API
  slug: wizehire-interviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wizehire/openapi/wizehire-interviews-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: is at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations of the United States Department of Commerce
  - summary: Limited to Market geography
    text: The Services are provided by Wizehire for use by Customer within and limited to the geographic boundaries of the Market.
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
name: WizeHire
provenance_date: '2026-11-10'
provider_name: WizeHire
provider_slug: wizehire
slug: wizehire-eligibility
source_date: '2026-11-10'
source_filename: wizehire-eligibility.yml
source_heading: Eligibility
source_page: https://wizehire.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WizeHire\naid: wizehire\nurl: https://wizehire.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services,\n    Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or\n    regulations of the United States Department of Commerce\n- summary: Limited to Market geography\n  text: The Services are provided by Wizehire for use by Customer within and\
  \ limited to the geographic boundaries\n    of the Market.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/wizehire/eligibility/wizehire-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from WizeHire's own page on 2026-11-10.
synthetic: false
tags:
- Hiring
- Recruiting
- Applicant Tracking
- Human Resources
- Talent Assessment
- Small Business
- Artificial Intelligence
- Job Board
- Onboarding
---
