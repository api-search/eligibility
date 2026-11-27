---
api_specs:
- filename: charmhealth-appointment-api-openapi.yml
  format: yaml
  label: CharmHealth Appointment API
  slug: charmhealth-appointment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-appointment-api-openapi.yml
- filename: charmhealth-capability-api-openapi.yml
  format: yaml
  label: CharmHealth Capability API
  slug: charmhealth-capability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-capability-api-openapi.yml
- filename: charmhealth-careteam-api-openapi.yml
  format: yaml
  label: CharmHealth CareTeam API
  slug: charmhealth-careteam-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-careteam-api-openapi.yml
- filename: charmhealth-condition-api-openapi.yml
  format: yaml
  label: CharmHealth Condition API
  slug: charmhealth-condition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-condition-api-openapi.yml
- filename: charmhealth-encounter-api-openapi.yml
  format: yaml
  label: CharmHealth Encounter API
  slug: charmhealth-encounter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-encounter-api-openapi.yml
- filename: charmhealth-immunization-api-openapi.yml
  format: yaml
  label: CharmHealth Immunization API
  slug: charmhealth-immunization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-immunization-api-openapi.yml
- filename: charmhealth-observation-api-openapi.yml
  format: yaml
  label: CharmHealth Observation API
  slug: charmhealth-observation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-observation-api-openapi.yml
- filename: charmhealth-organization-api-openapi.yml
  format: yaml
  label: CharmHealth Organization API
  slug: charmhealth-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-organization-api-openapi.yml
- filename: charmhealth-patient-api-openapi.yml
  format: yaml
  label: CharmHealth Patient API
  slug: charmhealth-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-patient-api-openapi.yml
- filename: charmhealth-practitioner-api-openapi.yml
  format: yaml
  label: CharmHealth Practitioner API
  slug: charmhealth-practitioner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-practitioner-api-openapi.yml
- filename: charmhealth-allergy-intolerance-api-openapi.yml
  format: yaml
  label: CharmHealth Allergy Intolerance API
  slug: charmhealth-allergy-intolerance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-allergy-intolerance-api-openapi.yml
- filename: charmhealth-care-plan-api-openapi.yml
  format: yaml
  label: CharmHealth Care plan API
  slug: charmhealth-care-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-care-plan-api-openapi.yml
- filename: charmhealth-document-reference-api-openapi.yml
  format: yaml
  label: CharmHealth Document Reference API
  slug: charmhealth-document-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-document-reference-api-openapi.yml
- filename: charmhealth-medication-request-api-openapi.yml
  format: yaml
  label: CharmHealth Medication Request API
  slug: charmhealth-medication-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/charmhealth/openapi/charmhealth-medication-request-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: All other users of your organization must also sign up for user accounts
    type: business
  minimum_age:
    text: You must be at least 18 years of age to enter into this binding agreement.
    value: '18'
  restricted_uses:
  - summary: Surescripts prescribing transactions limited to licensed providers
    text: You hereby represent and warrant that you are a licensed physician or other health care provider who is duly licensed or registered with the appropriate governmental authority to issue prescription orders
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
name: CharmHealth
provenance_date: '2026-11-09'
provider_name: CharmHealth
provider_slug: charmhealth
slug: charmhealth-eligibility
source_date: '2026-11-09'
source_filename: charmhealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.charmhealth.com/ehr/termsofservice.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CharmHealth\naid: charmhealth\nurl: https://www.charmhealth.com/ehr/termsofservice.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: All other users of your organization must also sign up for user accounts\nrestricted_uses:\n- summary: Surescripts prescribing transactions limited to licensed providers\n  text: You hereby represent and warrant that you are a licensed physician or other health care provider who is\n    duly licensed or registered with the appropriate governmental authority to issue prescription orders\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to enter into this binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/charmhealth/eligibility/charmhealth-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CharmHealth's own page on 2026-11-09.
synthetic: false
tags:
- Electronic Health Records
- FHIR
- Healthcare
- HL7
- Patient Engagement
- Patients
- SMART on FHIR
- US Core
---
