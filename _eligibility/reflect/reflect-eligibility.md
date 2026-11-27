---
api_specs:
- filename: reflect-execution-api-openapi.yml
  format: yaml
  label: Reflect Execution API
  slug: reflect-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reflect/openapi/reflect-execution-api-openapi.yml
- filename: reflect-executions-api-openapi.yml
  format: yaml
  label: Reflect Executions API
  slug: reflect-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reflect/openapi/reflect-executions-api-openapi.yml
- filename: reflect-tests-api-openapi.yml
  format: yaml
  label: Reflect Tests API
  slug: reflect-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reflect/openapi/reflect-tests-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Governing law depends on whether Customer is located in the U.S. or Canada. No served or excluded countries are listed.
  entity_types:
  - text: If the individual accepting this Agreement does so on behalf of a company or other entity, that individual represents and warrants that they have the legal authority to bind such entity to this Agreement.
    type: business
  - text: If Customer is a U.S. federal government department or agency or contracting on behalf of such department or agency, the Solutions were developed at private expense and are "Commercial Items"
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted Data
    text: 'Customer and its Users shall not upload, transmit, or otherwise provide to SmartBear any Customer Data subject to heightened legal or regulatory protections (“Restricted Data”), including but not limited to: (i) classified or export-controlled data (e.g., ITAR, EAR); (ii) regulated health, financial, or payment card data (e.g., HIPAA, GLBA, PCI DSS); or (iii) sensitive or special category personal data as defined under applicable privacy laws.'
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
name: Reflect
provenance_date: '2026-11-10'
provider_name: Reflect
provider_slug: reflect
slug: reflect-eligibility
source_date: '2026-11-10'
source_filename: reflect-eligibility.yml
source_heading: Eligibility
source_page: https://smartbear.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reflect\naid: reflect\nurl: https://smartbear.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Governing law depends on whether Customer is located in the U.S. or Canada. No served or excluded countries\n    are listed.\nentity_types:\n- type: business\n  text: If the individual accepting this Agreement does so on behalf of a company or other entity, that individual\n    represents and warrants that they have the legal authority to bind such entity to this Agreement.\n- type: government\n  text: If Customer is a U.S. federal government department or agency or contracting\
  \ on behalf of such department\n    or agency, the Solutions were developed at private expense and are \"Commercial Items\"\nrestricted_uses:\n- summary: Restricted Data\n  text: 'Customer and its Users shall not upload, transmit, or otherwise provide to SmartBear any Customer Data\n    subject to heightened legal or regulatory protections (“Restricted Data”), including but not limited to: (i)\n    classified or export-controlled data (e.g., ITAR, EAR); (ii) regulated health, financial, or payment card data\n    (e.g., HIPAA, GLBA, PCI DSS); or (iii) sensitive or special category personal data as defined under applicable\n    privacy laws.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reflect/eligibility/reflect-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Reflect's own page on 2026-11-10.
synthetic: false
tags:
- AI Testing
- Artificial Intelligence
- Automated Testing
- CI/CD
- Developer Tools
- End-to-End Testing
- QA
- Testing
---
