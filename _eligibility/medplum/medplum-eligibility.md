---
api_specs:
- filename: medplum-fhir-api-openapi.yml
  format: yaml
  label: Medplum Fhir API
  slug: medplum-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medplum/openapi/medplum-fhir-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"You" and "users" shall mean all health service providers and their agents who use the Medplum Service.'
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: CPT content internal use only
    text: solely for your internal use within the territory in which the AMA has authorized Medplum to distribute CPT content
  - summary: No AI training on CPT content
    text: You may not use CPT content to train, fine-tune, or otherwise adapt any artificial intelligence or machine learning model
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may take steps to verify you are a health service provider.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Medplum
provenance_date: '2026-11-10'
provider_name: Medplum
provider_slug: medplum
slug: medplum-eligibility
source_date: '2026-11-10'
source_filename: medplum-eligibility.yml
source_heading: Eligibility
source_page: https://www.medplum.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Medplum\naid: medplum\nurl: https://www.medplum.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: '\"You\" and \"users\" shall mean all health service providers and their agents who use the Medplum Service.'\nrestricted_uses:\n- summary: CPT content internal use only\n  text: solely for your internal use within the territory in which the AMA has authorized Medplum to distribute\n    CPT content\n- summary: No AI training on CPT content\n  text: You may not use CPT content to train, fine-tune, or otherwise adapt\
  \ any artificial intelligence or machine\n    learning model\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may take steps to verify you are a health service provider.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/medplum/eligibility/medplum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Medplum's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- FHIR
- Open Source
- Developer Platform
- HIPAA
- SMART on FHIR
- Clinical
- Interoperability
---
