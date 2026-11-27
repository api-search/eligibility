---
api_specs:
- filename: paper-instruments-openapi-generated.yml
  format: yaml
  label: Paper Instruments API
  slug: paper-instruments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paper-instruments/openapi/_ae-authored/paper-instruments-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located or ordinarily resident in any country or region subject to comprehensive U.S. sanctions
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to use the Services.
    type: individual
  - text: If you accept these Terms on behalf of an organization, you represent that you have authority to bind that organization
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use the Services.
    value: '18'
  restricted_uses:
  - summary: No decisions with legal or similar significant effects
    text: Use the Services to make decisions with legal or similarly significant effects on individuals, such as decisions about credit, employment, housing, or insurance, in violation of applicable law.
  - summary: No protected health information without agreement
    text: Unless we agree otherwise in writing, you will not use the Services to process protected health information
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You accept these Terms by checking a box when you first sign in to the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Paper Instruments
provenance_date: '2026-11-10'
provider_name: Paper Instruments
provider_slug: paper-instruments
slug: paper-instruments-eligibility
source_date: '2026-11-10'
source_filename: paper-instruments-eligibility.yml
source_heading: Eligibility
source_page: https://www.paperinstruments.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paper Instruments\naid: paper-instruments\nurl: https://www.paperinstruments.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located or ordinarily resident in any country or region subject to comprehensive\n    U.S. sanctions\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to use the Services.\n- type: business\n  text: If you accept these Terms on behalf of an organization, you represent that you have authority to bind that\n    organization\nrestricted_uses:\n- summary: No\
  \ decisions with legal or similar significant effects\n  text: Use the Services to make decisions with legal or similarly significant effects on individuals, such as decisions\n    about credit, employment, housing, or insurance, in violation of applicable law.\n- summary: No protected health information without agreement\n  text: Unless we agree otherwise in writing, you will not use the Services to process protected health information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You accept these Terms by checking a box when you first sign in to the Services\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/paper-instruments/eligibility/paper-instruments-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Paper Instruments's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Open Source
- Finance
- Consulting
- Law
---
