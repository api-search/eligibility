---
api_specs:
- filename: roivant-sciences-allergies-api-openapi.yml
  format: yaml
  label: Roivant Sciences Allergies API
  slug: roivant-sciences-allergies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-allergies-api-openapi.yml
- filename: roivant-sciences-appointments-api-openapi.yml
  format: yaml
  label: Roivant Sciences Appointments API
  slug: roivant-sciences-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-appointments-api-openapi.yml
- filename: roivant-sciences-diagnoses-api-openapi.yml
  format: yaml
  label: Roivant Sciences Diagnoses API
  slug: roivant-sciences-diagnoses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-diagnoses-api-openapi.yml
- filename: roivant-sciences-documents-api-openapi.yml
  format: yaml
  label: Roivant Sciences Documents API
  slug: roivant-sciences-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-documents-api-openapi.yml
- filename: roivant-sciences-encounters-api-openapi.yml
  format: yaml
  label: Roivant Sciences Encounters API
  slug: roivant-sciences-encounters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-encounters-api-openapi.yml
- filename: roivant-sciences-immunizations-api-openapi.yml
  format: yaml
  label: Roivant Sciences Immunizations API
  slug: roivant-sciences-immunizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-immunizations-api-openapi.yml
- filename: roivant-sciences-labs-api-openapi.yml
  format: yaml
  label: Roivant Sciences Labs API
  slug: roivant-sciences-labs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-labs-api-openapi.yml
- filename: roivant-sciences-medications-api-openapi.yml
  format: yaml
  label: Roivant Sciences Medications API
  slug: roivant-sciences-medications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-medications-api-openapi.yml
- filename: roivant-sciences-patients-api-openapi.yml
  format: yaml
  label: Roivant Sciences Patients API
  slug: roivant-sciences-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-patients-api-openapi.yml
- filename: roivant-sciences-practices-api-openapi.yml
  format: yaml
  label: Roivant Sciences Practices API
  slug: roivant-sciences-practices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-practices-api-openapi.yml
- filename: roivant-sciences-procedures-api-openapi.yml
  format: yaml
  label: Roivant Sciences Procedures API
  slug: roivant-sciences-procedures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-procedures-api-openapi.yml
- filename: roivant-sciences-providers-api-openapi.yml
  format: yaml
  label: Roivant Sciences Providers API
  slug: roivant-sciences-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-providers-api-openapi.yml
- filename: roivant-sciences-vitals-api-openapi.yml
  format: yaml
  label: Roivant Sciences Vitals API
  slug: roivant-sciences-vitals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/roivant-sciences/openapi/roivant-sciences-vitals-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    - CH
    text: Our Website is targeted at and intended for visitors residing in the United States, the United Kingdom, and Switzerland.
  entity_types:
  - text: You must be the age of majority in your jurisdiction (18 years in most U.S. states, the United Kingdom, and Switzerland) or older to use our Website.
    type: individual
  minimum_age:
    text: 18 years in most U.S. states, the United Kingdom, and Switzerland
    value: '18'
  restricted_uses:
  - summary: Commercial or business use
    text: may not be exploited in connection with any business or commercial purpose, without the prior express written permission of Roivant.
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
name: Roivant Sciences
provenance_date: '2026-11-10'
provider_name: Roivant Sciences
provider_slug: roivant-sciences
slug: roivant-sciences-eligibility
source_date: '2026-11-10'
source_filename: roivant-sciences-eligibility.yml
source_heading: Eligibility
source_page: https://www.roivant.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roivant Sciences\naid: roivant-sciences\nurl: https://www.roivant.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  - CH\n  excluded: []\n  text: Our Website is targeted at and intended for visitors residing in the United States, the United Kingdom,\n    and Switzerland.\nentity_types:\n- type: individual\n  text: You must be the age of majority in your jurisdiction (18 years in most U.S. states, the United Kingdom,\n    and Switzerland) or older to use our Website.\nrestricted_uses:\n- summary: Commercial or business use\n  text: may not be exploited in connection with any\
  \ business or commercial purpose, without the prior express written\n    permission of Roivant.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 18 years in most U.S. states, the United Kingdom, and Switzerland\n"
source_yaml_url: https://artifacts.apis.io/roivant-sciences/eligibility/roivant-sciences-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Roivant Sciences's own page on 2026-11-10.
synthetic: false
tags:
- Biotechnology
- Pharmaceuticals
- Drug Development
- Clinical Trials
- Health Data
- Electronic Health Records
- Real-World Evidence
- Holding Company
- Healthcare
---
