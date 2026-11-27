---
api_specs:
- filename: independence-blue-cross-formulary-api-openapi.yml
  format: yaml
  label: Independence Blue Cross Formulary API
  slug: independence-blue-cross-formulary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/independence-blue-cross/openapi/independence-blue-cross-formulary-api-openapi.yml
- filename: independence-blue-cross-patient-access-api-openapi.yml
  format: yaml
  label: Independence Blue Cross Patient Access API
  slug: independence-blue-cross-patient-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/independence-blue-cross/openapi/independence-blue-cross-patient-access-api-openapi.yml
- filename: independence-blue-cross-provider-directory-api-openapi.yml
  format: yaml
  label: Independence Blue Cross Provider Directory API
  slug: independence-blue-cross-provider-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/independence-blue-cross/openapi/independence-blue-cross-provider-directory-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the developer that employs or contracts you (“Your Company”) subject to your agreement to the Terms and Conditions
    type: business
  minimum_age:
    text: By using the Service, you affirm that you are of legal age to enter into these Terms and Conditions
    value: null
  restricted_uses:
  - summary: Patient Access API only with enrollee approval
    text: You may not access, connect to, retrieve data from, or use i n any way the Patient Access API except with the approval and at the direction of the applicable IBC enrollee or the enrollee’s personal representative.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You, and Your Company, and your application may only access, connect to, and/or retrieve data from each of the APIs after you and your application have successfully registered with IBC for access to the applicable API.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Independence Blue Cross
provenance_date: '2026-11-09'
provider_name: Independence Blue Cross
provider_slug: independence-blue-cross
slug: independence-blue-cross-eligibility
source_date: '2026-11-09'
source_filename: independence-blue-cross-eligibility.yml
source_heading: Eligibility
source_page: https://www.ibx.com/htdocs/custom/tnc/Developer%20Portal%20TandC.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Independence Blue Cross\naid: independence-blue-cross\nurl: https://www.ibx.com/htdocs/custom/tnc/Developer%20Portal%20TandC.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the developer that employs or contracts you (“Your Company”) subject to your agreement to the Terms and\n    Conditions\nrestricted_uses:\n- summary: Patient Access API only with enrollee approval\n  text: You may not access, connect to, retrieve data from, or use i n any way the Patient Access API except with\n    the approval and at the direction of the applicable\
  \ IBC enrollee or the enrollee’s personal representative.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You, and Your Company, and your application may only access, connect to, and/or retrieve data from each\n    of the APIs after you and your application have successfully registered with IBC for access to the applicable\n    API.\nminimum_age:\n  value: null\n  text: By using the Service, you affirm that you are of legal age to enter into these Terms and Conditions\n"
source_yaml_url: https://artifacts.apis.io/independence-blue-cross/eligibility/independence-blue-cross-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Independence Blue Cross's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Health Insurance
- Blue Cross Blue Shield
- Managed Care
- Medicare
- Medicare Advantage
- Medicaid
- CHIP
- Commercial
- Dental
- Vision
- Behavioral Health
- Pharmacy Benefits
- Interoperability
- FHIR
- SMART on FHIR
- CMS
- Patient Access
- Provider Directory
- Drug Formulary
- Transparency In Coverage
---
