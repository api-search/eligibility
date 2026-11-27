---
api_specs:
- filename: general-translation-context-api-openapi.yml
  format: yaml
  label: General Translation Context API
  slug: general-translation-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/general-translation/openapi/general-translation-context-api-openapi.yml
- filename: general-translation-files-api-openapi.yml
  format: yaml
  label: General Translation Files API
  slug: general-translation-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/general-translation/openapi/general-translation-files-api-openapi.yml
- filename: general-translation-project-api-openapi.yml
  format: yaml
  label: General Translation Project API
  slug: general-translation-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/general-translation/openapi/general-translation-project-api-openapi.yml
- filename: general-translation-translation-api-openapi.yml
  format: yaml
  label: General Translation API
  slug: general-translation-translation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/general-translation/openapi/general-translation-translation-api-openapi.yml
- filename: general-translation-context-management-api-openapi.yml
  format: yaml
  label: General Translation Context Management API
  slug: general-translation-context-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/general-translation/openapi/general-translation-context-management-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only you, if you are an individual Customer, and your employees or contractors acting in such capacity
    type: individual
  - text: in the case of an individual accepting these terms on behalf of a company or other legal entity, the company or other legal entity for which such individual is accepting this Agreement
    type: business
  - text: If you or any of your Users is an agency, department, or other entity of the United States Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: You will comply with all relevant U.S. and foreign export and import Laws in using the GT Technology.
  - summary: No ITAR-controlled information
    text: will not submit to the GT Technology any information controlled under the U.S. International Traffic in Arms Regulations.
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
name: General Translation
provenance_date: '2026-11-09'
provider_name: General Translation
provider_slug: general-translation
slug: general-translation-eligibility
source_date: '2026-11-09'
source_filename: general-translation-eligibility.yml
source_heading: Eligibility
source_page: https://generaltranslation.com/en-US/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: General Translation\naid: general-translation\nurl: https://generaltranslation.com/en-US/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only you, if you are an individual Customer, and your employees or contractors acting in such capacity\n- type: business\n  text: in the case of an individual accepting these terms on behalf of a company or other legal entity, the company\n    or other legal entity for which such individual is accepting this Agreement\n- type: government\n  text: If you or any of your Users is an agency,\
  \ department, or other entity of the United States Government\nrestricted_uses:\n- summary: Export restrictions\n  text: You will comply with all relevant U.S. and foreign export and import Laws in using the GT Technology.\n- summary: No ITAR-controlled information\n  text: will not submit to the GT Technology any information controlled under the U.S. International Traffic in\n    Arms Regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/general-translation/eligibility/general-translation-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from General Translation's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Internationalization
- Localization
- Translation
- Developer Tools
- Artificial Intelligence
- i18n
- SDK
- Machine Translation
---
