---
api_specs:
- filename: meditech-allergy-api-openapi.yml
  format: yaml
  label: meditech Allergy API
  slug: meditech-allergy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-allergy-api-openapi.yml
- filename: meditech-capability-api-openapi.yml
  format: yaml
  label: meditech Capability API
  slug: meditech-capability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-capability-api-openapi.yml
- filename: meditech-condition-api-openapi.yml
  format: yaml
  label: meditech Condition API
  slug: meditech-condition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-condition-api-openapi.yml
- filename: meditech-diagnostic-api-openapi.yml
  format: yaml
  label: meditech Diagnostic API
  slug: meditech-diagnostic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-diagnostic-api-openapi.yml
- filename: meditech-encounter-api-openapi.yml
  format: yaml
  label: meditech Encounter API
  slug: meditech-encounter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-encounter-api-openapi.yml
- filename: meditech-medication-api-openapi.yml
  format: yaml
  label: meditech Medication API
  slug: meditech-medication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-medication-api-openapi.yml
- filename: meditech-observation-api-openapi.yml
  format: yaml
  label: meditech Observation API
  slug: meditech-observation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-observation-api-openapi.yml
- filename: meditech-patient-api-openapi.yml
  format: yaml
  label: meditech Patient API
  slug: meditech-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meditech/openapi/meditech-patient-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are at least 18 years of age and that you possess the legal right and ability to agree to these Terms
    type: individual
  - text: If you are using the MEDITECH API on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  minimum_age:
    text: You represent and warrant that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No sublicensing or sale of data
    text: Sell, lease or sublicense the MEDITECH API or any data derived through the MEDITECH API
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You agree to register your app with an HCO that has implemented the MEDITECH API.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MEDITECH
provenance_date: '2026-11-10'
provider_name: MEDITECH
provider_slug: meditech
slug: meditech-eligibility
source_date: '2026-11-10'
source_filename: meditech-eligibility.yml
source_heading: Eligibility
source_page: https://home.meditech.com/en/d/restapiresources/pages/apiterms.htm
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MEDITECH\naid: meditech\nurl: https://home.meditech.com/en/d/restapiresources/pages/apiterms.htm\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are at least 18 years of age and that you possess the legal right and\n    ability to agree to these Terms\n- type: business\n  text: If you are using the MEDITECH API on behalf of an entity, you represent and warrant that you have authority\n    to bind that entity to the Terms\nrestricted_uses:\n- summary: No sublicensing or sale of data\n  text: Sell,\
  \ lease or sublicense the MEDITECH API or any data derived through the MEDITECH API\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You agree to register your app with an HCO that has implemented the MEDITECH API.\nminimum_age:\n  value: '18'\n  text: You represent and warrant that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/meditech/eligibility/meditech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from MEDITECH's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Electronic Health Records
- Healthcare
- FHIR
- HL7
- Interoperability
---
