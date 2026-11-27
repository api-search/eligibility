---
api_specs:
- filename: mocklab-openapi-generated.yml
  format: yaml
  label: MockLab API
  slug: mocklab-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mocklab/openapi/_ae-authored/mocklab-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - IR
    - LB
    - SD
    - SY
    - KP
    - CU
    - LY
    - IQ
    served: []
    text: the Customer represents and warrant that it is not located in Iran, Lebanon, Sudan, Syria,North Korea, Cuba, Libya or Iraq.
  entity_types:
  - text: The individual (the “User”) opening an account onWireMock (the “Account”) does this on behalf of his/her organization (the “Customer”).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No illegal or unauthorized use
    text: It will not use the Service for any illegal or unauthorized purpose
  - summary: No personal data
    text: contains any information relating to an identified or identifiable natural person (the “Personal Data”)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- LB
- SD
- SY
- KP
- CU
- LY
- IQ
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MockLab
provenance_date: '2026-11-10'
provider_name: MockLab
provider_slug: mocklab
slug: mocklab-eligibility
source_date: '2026-11-10'
source_filename: mocklab-eligibility.yml
source_heading: Eligibility
source_page: https://www.wiremock.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MockLab\naid: mocklab\nurl: https://www.wiremock.io/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - LB\n  - SD\n  - SY\n  - KP\n  - CU\n  - LY\n  - IQ\n  text: the Customer represents and warrant that it is not located in Iran, Lebanon, Sudan, Syria,North Korea, Cuba,\n    Libya or Iraq.\nentity_types:\n- type: business\n  text: The individual (the “User”) opening an account onWireMock (the “Account”) does this on behalf of his/her\n    organization (the “Customer”).\nrestricted_uses:\n- summary: No illegal or unauthorized use\n  text: It will not use the Service\
  \ for any illegal or unauthorized purpose\n- summary: No personal data\n  text: contains any information relating to an identified or identifiable natural person (the “Personal Data”)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mocklab/eligibility/mocklab-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from MockLab's own page on 2026-11-10.
synthetic: false
tags:
- API Mocking
- Environment Simulation
- Testing
- Fintech
- Service Virtualization
---
