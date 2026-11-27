---
api_specs:
- filename: kno2-attachments-api-openapi.yml
  format: yaml
  label: Kno2 Attachments API
  slug: kno2-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kno2/openapi/kno2-attachments-api-openapi.yml
- filename: kno2-authentication-api-openapi.yml
  format: yaml
  label: Kno2 Authentication API
  slug: kno2-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kno2/openapi/kno2-authentication-api-openapi.yml
- filename: kno2-directory-api-openapi.yml
  format: yaml
  label: Kno2 Directory API
  slug: kno2-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kno2/openapi/kno2-directory-api-openapi.yml
- filename: kno2-intake-api-openapi.yml
  format: yaml
  label: Kno2 Intake API
  slug: kno2-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kno2/openapi/kno2-intake-api-openapi.yml
- filename: kno2-messaging-api-openapi.yml
  format: yaml
  label: Kno2 Messaging API
  slug: kno2-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kno2/openapi/kno2-messaging-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you and the organization you represent are not located in, under the control of, or a national or resident of any restricted country.
  entity_types:
  - text: The System is a service for healthcare organizations
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial clinical use only
    text: You may use the System only for the transmission of bona fide non-commercial and clinical information.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you will need to complete an Identity Proofing process using NIST level 3 criteria. Identity Proofing must be completed by your organization periodically and in the event your user account is disabled.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kno2
provenance_date: '2026-11-09'
provider_name: Kno2
provider_slug: kno2
slug: kno2-eligibility
source_date: '2026-11-09'
source_filename: kno2-eligibility.yml
source_heading: Eligibility
source_page: https://kno2.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kno2\naid: kno2\nurl: https://kno2.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you and the organization you represent are not located in, under the control\n    of, or a national or resident of any restricted country.\nentity_types:\n- type: business\n  text: The System is a service for healthcare organizations\nrestricted_uses:\n- summary: Non-commercial clinical use only\n  text: You may use the System only for the transmission of bona fide non-commercial and clinical information.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: you will need to complete an Identity Proofing process using NIST level 3 criteria. Identity Proofing must\n    be completed by your organization periodically and in the event your user account is disabled.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kno2/eligibility/kno2-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Kno2's own page on 2026-11-09.
synthetic: false
tags:
- Interoperability
- Clinical Records
- Health Information Exchange
- Direct Secure Messaging
- FHIR
- Clinical Documents
- Patient Records
- Healthcare
- HIE
- Care Coordination
- QHIN
- TEFCA
- Carequality
---
