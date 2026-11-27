---
api_specs:
- filename: lifen-communicationrequest-api-openapi.yml
  format: yaml
  label: Lifen CommunicationRequest API
  slug: lifen-communicationrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-communicationrequest-api-openapi.yml
- filename: lifen-coverage-api-openapi.yml
  format: yaml
  label: Lifen Coverage API
  slug: lifen-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-coverage-api-openapi.yml
- filename: lifen-encounter-api-openapi.yml
  format: yaml
  label: Lifen Encounter API
  slug: lifen-encounter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-encounter-api-openapi.yml
- filename: lifen-organization-api-openapi.yml
  format: yaml
  label: Lifen Organization API
  slug: lifen-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-organization-api-openapi.yml
- filename: lifen-patient-api-openapi.yml
  format: yaml
  label: Lifen Patient API
  slug: lifen-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-patient-api-openapi.yml
- filename: lifen-practitioner-api-openapi.yml
  format: yaml
  label: Lifen Practitioner API
  slug: lifen-practitioner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-practitioner-api-openapi.yml
- filename: lifen-token-api-openapi.yml
  format: yaml
  label: Lifen Token API
  slug: lifen-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lifen/openapi/lifen-token-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: L’accès à la Plateforme Lifen est réservé aux personnes physiques de plus de 18 ans.
    type: individual
  minimum_age:
    text: L’accès à la Plateforme Lifen est réservé aux personnes physiques de plus de 18 ans.
    value: '18'
  restricted_uses:
  - summary: Not telemedicine, medical device or emergency service
    text: 'Les Services Lifen ne sont pas : 1) un outil de télé expertise, ou plus généralement de télémédecine'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Lifen s’assure de l’identité de l’Utilisateur avant toute création d’un Compte Lifen.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lifen
provenance_date: '2026-11-09'
provider_name: Lifen
provider_slug: lifen
slug: lifen-eligibility
source_date: '2026-11-09'
source_filename: lifen-eligibility.yml
source_heading: Eligibility
source_page: https://www.lifen.fr/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lifen\naid: lifen\nurl: https://www.lifen.fr/cgu\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: L’accès à la Plateforme Lifen est réservé aux personnes physiques de plus de 18 ans.\nrestricted_uses:\n- summary: Not telemedicine, medical device or emergency service\n  text: 'Les Services Lifen ne sont pas : 1) un outil de télé expertise, ou plus généralement de télémédecine'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Lifen s’assure de l’identité de l’Utilisateur avant toute création\
  \ d’un Compte Lifen.\nminimum_age:\n  value: '18'\n  text: L’accès à la Plateforme Lifen est réservé aux personnes physiques de plus de 18 ans.\n"
source_yaml_url: https://artifacts.apis.io/lifen/eligibility/lifen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Lifen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- FHIR
- Interoperability
- Health Data
- Electronic Health Records
- Medical Documents
- Secure Messaging
- France
- HL7
---
