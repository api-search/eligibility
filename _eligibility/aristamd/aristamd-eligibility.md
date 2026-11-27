---
api_specs:
- filename: aristamd-comments-api-openapi.yml
  format: yaml
  label: AristaMD Comments API
  slug: aristamd-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-comments-api-openapi.yml
- filename: aristamd-diagnostic-api-openapi.yml
  format: yaml
  label: AristaMD Diagnostic API
  slug: aristamd-diagnostic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-diagnostic-api-openapi.yml
- filename: aristamd-econsults-api-openapi.yml
  format: yaml
  label: AristaMD E Consults API
  slug: aristamd-econsults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-econsults-api-openapi.yml
- filename: aristamd-intergy-patients-api-openapi.yml
  format: yaml
  label: AristaMD Intergy/Patients API
  slug: aristamd-intergy-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-intergy-patients-api-openapi.yml
- filename: aristamd-panelists-api-openapi.yml
  format: yaml
  label: AristaMD Panelists API
  slug: aristamd-panelists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-panelists-api-openapi.yml
- filename: aristamd-patients-api-openapi.yml
  format: yaml
  label: AristaMD Patients API
  slug: aristamd-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-patients-api-openapi.yml
- filename: aristamd-requests-api-openapi.yml
  format: yaml
  label: AristaMD Requests API
  slug: aristamd-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-requests-api-openapi.yml
- filename: aristamd-reviews-api-openapi.yml
  format: yaml
  label: AristaMD Reviews API
  slug: aristamd-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-reviews-api-openapi.yml
- filename: aristamd-specialties-api-openapi.yml
  format: yaml
  label: AristaMD Specialties API
  slug: aristamd-specialties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-specialties-api-openapi.yml
- filename: aristamd-specialty-api-openapi.yml
  format: yaml
  label: AristaMD Specialty API
  slug: aristamd-specialty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-specialty-api-openapi.yml
- filename: aristamd-users-api-openapi.yml
  format: yaml
  label: AristaMD Users API
  slug: aristamd-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-users-api-openapi.yml
- filename: aristamd-workup-checklists-api-openapi.yml
  format: yaml
  label: AristaMD Workup Checklists API
  slug: aristamd-workup-checklists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aristamd/openapi/aristamd-workup-checklists-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are not available to Users located outside the United States.
  entity_types:
  - text: 'Access to and use of the Services is limited exclusively to individuals who are: (1) at least 18 years of age; and (2) located in a State where the Services are available at the time Services are to be rendered.'
    type: individual
  minimum_age:
    text: (1) at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Medical emergencies
    text: The Services are not for medical emergencies.
  - summary: No DEA controlled substance prescribing
    text: MEDICAL GROUP PROVIDERS DO NOT PRESCRIBE DEA CONTROLLED SUBSTANCES, SUCH AS THOSE CONTAINING OPIOIDS OR AMPHETAMINES.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you do not provide this information in the manner requested within fourteen (14) days of the request, we reserve the right to suspend, discontinue, or deny your access to and use of the Services until you provide the information to us as requested.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AristaMD
provenance_date: '2026-11-09'
provider_name: AristaMD
provider_slug: aristamd
slug: aristamd-eligibility
source_date: '2026-11-09'
source_filename: aristamd-eligibility.yml
source_heading: Eligibility
source_page: https://www.aristamd.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AristaMD\naid: aristamd\nurl: https://www.aristamd.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to Users located outside the United States.\nentity_types:\n- type: individual\n  text: 'Access to and use of the Services is limited exclusively to individuals who are: (1) at least 18 years\n    of age; and (2) located in a State where the Services are available at the time Services are to be rendered.'\nrestricted_uses:\n- summary: Medical emergencies\n  text: The Services are not for medical emergencies.\n- summary: No DEA controlled\
  \ substance prescribing\n  text: MEDICAL GROUP PROVIDERS DO NOT PRESCRIBE DEA CONTROLLED SUBSTANCES, SUCH AS THOSE CONTAINING OPIOIDS OR\n    AMPHETAMINES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you do not provide this information in the manner requested within fourteen (14) days of the request,\n    we reserve the right to suspend, discontinue, or deny your access to and use of the Services until you provide\n    the information to us as requested.\nminimum_age:\n  value: '18'\n  text: (1) at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/aristamd/eligibility/aristamd-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AristaMD's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Telehealth
- eConsult
- Specialty Care
- Referrals
- Care Coordination
- Health Plans
- Medicaid
- HL7
- Electronic Health Records
---
