---
api_specs:
- filename: relaygpu-com-openapi-generated.yml
  format: yaml
  label: relaygpu-com API
  slug: relaygpu-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relaygpu-com/openapi/_ae-authored/relaygpu-com-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: neither you nor any Authorized User is located, organized or ordinarily resident in a country or region subject to comprehensive US sanctions
  entity_types:
  - text: The Services are offered for business, professional and developer purposes.
    type: business
  - text: The Services are offered for business, professional and developer purposes.
    type: developer
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into contracts.
    value: '18'
  restricted_uses:
  - summary: Sensitive data submission
    text: you must not submit to the Services protected health information subject to HIPAA, payment card data, government identification numbers, or other sensitive personal data
  - summary: High-impact uses
    text: THE SERVICES ARE NOT DESIGNED FOR MEDICAL DIAGNOSIS OR TREATMENT, EMERGENCY RESPONSE, LEGAL DETERMINATIONS, EMPLOYMENT, CREDIT, INSURANCE OR HOUSING DECISIONS
  - summary: Prohibited end uses under export control
    text: You will not use the Services for any end use prohibited under US export control laws, including the development, production or use of nuclear, chemical or biological weapons or missiles.
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
name: relaygpu-com
provenance_date: '2026-11-10'
provider_name: relaygpu-com
provider_slug: relaygpu-com
slug: relaygpu-com-eligibility
source_date: '2026-11-10'
source_filename: relaygpu-com-eligibility.yml
source_heading: Eligibility
source_page: https://relaygpu.com/legals/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: relaygpu-com\naid: relaygpu-com\nurl: https://relaygpu.com/legals/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: neither you nor any Authorized User is located, organized or ordinarily resident in a country or region\n    subject to comprehensive US sanctions\nentity_types:\n- type: business\n  text: The Services are offered for business, professional and developer purposes.\n- type: developer\n  text: The Services are offered for business, professional and developer purposes.\nrestricted_uses:\n- summary: Sensitive data submission\n  text: you must not submit to the Services\
  \ protected health information subject to HIPAA, payment card data, government\n    identification numbers, or other sensitive personal data\n- summary: High-impact uses\n  text: THE SERVICES ARE NOT DESIGNED FOR MEDICAL DIAGNOSIS OR TREATMENT, EMERGENCY RESPONSE, LEGAL DETERMINATIONS,\n    EMPLOYMENT, CREDIT, INSURANCE OR HOUSING DECISIONS\n- summary: Prohibited end uses under export control\n  text: You will not use the Services for any end use prohibited under US export control laws, including the development,\n    production or use of nuclear, chemical or biological weapons or missiles.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into contracts.\n"
source_yaml_url: https://artifacts.apis.io/relaygpu-com/eligibility/relaygpu-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from relaygpu-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Compute
- GPU
- Cloud
---
