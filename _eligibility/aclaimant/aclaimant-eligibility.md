---
api_specs:
- filename: aclaimant-answers-api-openapi.yml
  format: yaml
  label: Aclaimant Answers API
  slug: aclaimant-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-answers-api-openapi.yml
- filename: aclaimant-bulk-api-openapi.yml
  format: yaml
  label: Aclaimant Bulk API
  slug: aclaimant-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-bulk-api-openapi.yml
- filename: aclaimant-companies-api-openapi.yml
  format: yaml
  label: Aclaimant Companies API
  slug: aclaimant-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-companies-api-openapi.yml
- filename: aclaimant-exposures-api-openapi.yml
  format: yaml
  label: Aclaimant Exposures API
  slug: aclaimant-exposures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-exposures-api-openapi.yml
- filename: aclaimant-incidents-api-openapi.yml
  format: yaml
  label: Aclaimant Incidents API
  slug: aclaimant-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-incidents-api-openapi.yml
- filename: aclaimant-policies-api-openapi.yml
  format: yaml
  label: Aclaimant Policies API
  slug: aclaimant-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-policies-api-openapi.yml
- filename: aclaimant-policy-programs-api-openapi.yml
  format: yaml
  label: Aclaimant Policy Programs API
  slug: aclaimant-policy-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aclaimant/openapi/aclaimant-policy-programs-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any use modification, reproduction, release, performance, display, or disclosure of such commercial software or commercial software documentation by the U.S. Government will be governed solely by the terms of this Agreement
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: US export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto
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
name: Aclaimant
provenance_date: '2026-11-09'
provider_name: Aclaimant
provider_slug: aclaimant
slug: aclaimant-eligibility
source_date: '2026-11-09'
source_filename: aclaimant-eligibility.yml
source_heading: Eligibility
source_page: https://www.aclaimant.com/service-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aclaimant\naid: aclaimant\nurl: https://www.aclaimant.com/service-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: any use modification, reproduction, release, performance, display, or disclosure of such commercial software\n    or commercial software documentation by the U.S. Government will be governed solely by the terms of this Agreement\nrestricted_uses:\n- summary: US export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services,\n    Software or\
  \ anything related thereto\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aclaimant/eligibility/aclaimant-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Aclaimant's own page on 2026-11-09.
synthetic: false
tags:
- Risk Management
- Insurance
- Claims Management
- Incident Management
- Safety
- RMIS
- Workers Compensation
- OSHA
- Enterprise Risk Management
- Insurtech
---
