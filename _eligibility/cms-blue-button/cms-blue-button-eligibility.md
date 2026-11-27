---
api_specs:
- filename: cms-blue-button-coverage-api-openapi.yml
  format: yaml
  label: CMS Blue Button 2.0 Coverage API
  slug: cms-blue-button-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-blue-button/openapi/cms-blue-button-coverage-api-openapi.yml
- filename: cms-blue-button-explanationofbenefit-api-openapi.yml
  format: yaml
  label: CMS Blue Button 2.0 ExplanationOfBenefit API
  slug: cms-blue-button-explanationofbenefit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-blue-button/openapi/cms-blue-button-explanationofbenefit-api-openapi.yml
- filename: cms-blue-button-metadata-api-openapi.yml
  format: yaml
  label: CMS Blue Button 2.0 Metadata API
  slug: cms-blue-button-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-blue-button/openapi/cms-blue-button-metadata-api-openapi.yml
- filename: cms-blue-button-patient-api-openapi.yml
  format: yaml
  label: CMS Blue Button 2.0 Patient API
  slug: cms-blue-button-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-blue-button/openapi/cms-blue-button-patient-api-openapi.yml
- filename: cms-blue-button-user-info-api-openapi.yml
  format: yaml
  label: CMS Blue Button 2.0 User Info API
  slug: cms-blue-button-user-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-blue-button/openapi/cms-blue-button-user-info-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Blue Button APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No implied CMS endorsement
    text: You may not use the CMS name, logo, or the like to imply endorsement of any product, service, or entity
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
name: CMS Blue Button 2.0
provenance_date: '2026-11-09'
provider_name: CMS Blue Button 2.0
provider_slug: cms-blue-button
slug: cms-blue-button-eligibility
source_date: '2026-11-09'
source_filename: cms-blue-button-eligibility.yml
source_heading: Eligibility
source_page: https://bluebutton.cms.gov/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CMS Blue Button 2.0\naid: cms-blue-button\nurl: https://bluebutton.cms.gov/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Blue Button APIs on behalf of an entity, you represent and warrant that you have authority\n    to bind that entity to the Terms\nrestricted_uses:\n- summary: No implied CMS endorsement\n  text: You may not use the CMS name, logo, or the like to imply endorsement of any product, service, or entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cms-blue-button/eligibility/cms-blue-button-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CMS Blue Button 2.0's own page on 2026-11-09.
synthetic: false
tags:
- Blue Button
- CARIN
- Medicare
- FHIR
- Claims Data
- Patient Access
- Healthcare
- Government
---
