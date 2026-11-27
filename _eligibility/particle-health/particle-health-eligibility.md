---
api_specs:
- filename: particle-health-authentication-api-openapi.yml
  format: yaml
  label: Particle Health Authentication API
  slug: particle-health-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-authentication-api-openapi.yml
- filename: particle-health-batches-api-openapi.yml
  format: yaml
  label: Particle Health Batches API
  slug: particle-health-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-batches-api-openapi.yml
- filename: particle-health-ccda-api-openapi.yml
  format: yaml
  label: Particle Health CCDA API
  slug: particle-health-ccda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-ccda-api-openapi.yml
- filename: particle-health-deltas-api-openapi.yml
  format: yaml
  label: Particle Health Deltas API
  slug: particle-health-deltas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-deltas-api-openapi.yml
- filename: particle-health-documents-api-openapi.yml
  format: yaml
  label: Particle Health Documents API
  slug: particle-health-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-documents-api-openapi.yml
- filename: particle-health-fhir-api-openapi.yml
  format: yaml
  label: Particle Health FHIR API
  slug: particle-health-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-fhir-api-openapi.yml
- filename: particle-health-files-api-openapi.yml
  format: yaml
  label: Particle Health Files API
  slug: particle-health-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-files-api-openapi.yml
- filename: particle-health-flat-api-openapi.yml
  format: yaml
  label: Particle Health Flat API
  slug: particle-health-flat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-flat-api-openapi.yml
- filename: particle-health-hl7v2-api-openapi.yml
  format: yaml
  label: Particle Health HL7v2 API
  slug: particle-health-hl7v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-hl7v2-api-openapi.yml
- filename: particle-health-networkparticipants-api-openapi.yml
  format: yaml
  label: Particle Health NetworkParticipants API
  slug: particle-health-networkparticipants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-networkparticipants-api-openapi.yml
- filename: particle-health-notifications-api-openapi.yml
  format: yaml
  label: Particle Health Notifications API
  slug: particle-health-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-notifications-api-openapi.yml
- filename: particle-health-patients-api-openapi.yml
  format: yaml
  label: Particle Health Patients API
  slug: particle-health-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-patients-api-openapi.yml
- filename: particle-health-projects-api-openapi.yml
  format: yaml
  label: Particle Health Projects API
  slug: particle-health-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-projects-api-openapi.yml
- filename: particle-health-providermap-api-openapi.yml
  format: yaml
  label: Particle Health ProviderMap API
  slug: particle-health-providermap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-providermap-api-openapi.yml
- filename: particle-health-queries-api-openapi.yml
  format: yaml
  label: Particle Health Queries API
  slug: particle-health-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-queries-api-openapi.yml
- filename: particle-health-signal-api-openapi.yml
  format: yaml
  label: Particle Health Signal API
  slug: particle-health-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-signal-api-openapi.yml
- filename: particle-health-subscriptions-api-openapi.yml
  format: yaml
  label: Particle Health Subscriptions API
  slug: particle-health-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/particle-health/openapi/particle-health-subscriptions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: in the event that you are signing up for a User Account on behalf of an organization, you represent that you have the legal authority to bind that organization to these Terms of Use
    type: business
  minimum_age:
    text: you represent that you (i) have the legal capacity (including, without limitation, being of sufficient age) to enter into contracts under the laws of the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Denied persons
    text: are not on a list of persons barred from receiving services under U.S. laws (including, without limitation, the Denied Persons List and the Entity List issued by the U.S. Department of Commerce, Bureau of Industry and Security)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you are required to open an account (“Your Account”) by registering with Particle Health. When you register for Your Account, you must provide true, accurate, current, and complete information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Particle Health
provenance_date: '2026-11-10'
provider_name: Particle Health
provider_slug: particle-health
slug: particle-health-eligibility
source_date: '2026-11-10'
source_filename: particle-health-eligibility.yml
source_heading: Eligibility
source_page: https://particlehealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Particle Health\naid: particle-health\nurl: https://particlehealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: in the event that you are signing up for a User Account on behalf of an organization, you represent that\n    you have the legal authority to bind that organization to these Terms of Use\nrestricted_uses:\n- summary: Denied persons\n  text: are not on a list of persons barred from receiving services under U.S. laws (including, without limitation,\n    the Denied Persons List and the Entity List issued by\
  \ the U.S. Department of Commerce, Bureau of Industry and\n    Security)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you are required to open an account (“Your Account”) by registering with Particle Health. When you register\n    for Your Account, you must provide true, accurate, current, and complete information\nminimum_age:\n  value: null\n  text: you represent that you (i) have the legal capacity (including, without limitation, being of sufficient age)\n    to enter into contracts under the laws of the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/particle-health/eligibility/particle-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Particle Health's own page on 2026-11-10.
synthetic: false
tags:
- ADT
- C-CDA
- Care Coordination
- Carequality
- Clinical Data
- CommonWell
- Deltas
- eHealth Exchange
- Electronic Health Records
- FHIR
- Health Data
- Health Information Exchange
- Healthcare
- HIE
- HL7
- HL7v2
- Interoperability
- Medical Records
- Patients
- Pharmacy
- QHIN
- Surescripts
- TEFCA
- USCDI
---
