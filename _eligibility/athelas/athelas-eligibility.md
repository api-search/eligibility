---
api_specs:
- filename: athelas-auth-api-openapi.yml
  format: yaml
  label: Athelas Auth API
  slug: athelas-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-auth-api-openapi.yml
- filename: athelas-patients-api-openapi.yml
  format: yaml
  label: Athelas Patients API
  slug: athelas-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-patients-api-openapi.yml
- filename: athelas-prescribers-api-openapi.yml
  format: yaml
  label: Athelas Prescribers API
  slug: athelas-prescribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-prescribers-api-openapi.yml
- filename: athelas-sites-api-openapi.yml
  format: yaml
  label: Athelas Sites API
  slug: athelas-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-sites-api-openapi.yml
- filename: athelas-test-types-api-openapi.yml
  format: yaml
  label: Athelas Test Types API
  slug: athelas-test-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/athelas/openapi/athelas-test-types-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must register to create an account (“User Account”) and become a “Registered User” to use the Services
    type: individual
  minimum_age:
    text: You are at least 18 years old and are otherwise legally qualified to enter into and form contracts under applicable law
    value: '18'
  restricted_uses:
  - summary: Not for emergency situations
    text: THE SERVICES ARE NOT INTENDED FOR EMERGENCY SITUATIONS.
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
name: Athelas
provenance_date: '2026-11-09'
provider_name: Athelas
provider_slug: athelas
slug: athelas-eligibility
source_date: '2026-11-09'
source_filename: athelas-eligibility.yml
source_heading: Eligibility
source_page: https://www.athelas.com/legal/general-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Athelas\naid: athelas\nurl: https://www.athelas.com/legal/general-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must register to create an account (“User Account”) and become a “Registered User” to use the Services\nrestricted_uses:\n- summary: Not for emergency situations\n  text: THE SERVICES ARE NOT INTENDED FOR EMERGENCY SITUATIONS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old and are otherwise legally qualified\
  \ to enter into and form contracts under\n    applicable law\n"
source_yaml_url: https://artifacts.apis.io/athelas/eligibility/athelas-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Athelas's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Remote Patient Monitoring
- Electronic Health Records
- FHIR
- Revenue Cycle Management
- Medical Devices
- SMART on FHIR
- Interoperability
- Artificial Intelligence
---
