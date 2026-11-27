---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is intended for individuals who are United States residents and who have reached the age of majority in their state of residence.
  entity_types:
  - text: This Website is intended for individuals who are United States residents and who have reached the age of majority in their state of residence.
    type: individual
  minimum_age:
    text: Individuals who have not reached the age of majority in their state of residence may not use the Website or its Services.
    value: age of majority in state of residence
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
name: PatientFi
provenance_date: '2026-11-10'
provider_name: PatientFi
provider_slug: patientfi
slug: patientfi-eligibility
source_date: '2026-11-10'
source_filename: patientfi-eligibility.yml
source_heading: Eligibility
source_page: https://patientfi.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PatientFi\naid: patientfi\nurl: https://patientfi.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is intended for individuals who are United States residents and who have reached the age of\n    majority in their state of residence.\nentity_types:\n- type: individual\n  text: This Website is intended for individuals who are United States residents and who have reached the age of\n    majority in their state of residence.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ age of majority in state of residence\n  text: Individuals who have not reached the age of majority in their state of residence may not use the Website\n    or its Services.\n"
source_yaml_url: https://artifacts.apis.io/patientfi/eligibility/patientfi-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from PatientFi's own page on 2026-11-10.
synthetic: false
tags:
- healthcare-financing
- Patient Financing
- Consumer Lending
- Point of Sale Financing
- Buy Now Pay Later
- Fintech
- Payments
- Embedded Finance
- Aesthetics
- Plastic Surgery
- Med Spa
- cosmetic-dental
- Fertility
- Audiology
- Practice Management
---
