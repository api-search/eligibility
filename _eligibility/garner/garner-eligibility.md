---
api_specs:
- filename: garner-facilities-api-openapi.yml
  format: yaml
  label: Garner Facilities API
  slug: garner-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-facilities-api-openapi.yml
- filename: garner-professionals-api-openapi.yml
  format: yaml
  label: Garner Professionals API
  slug: garner-professionals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-professionals-api-openapi.yml
- filename: garner-provider-annotations-api-openapi.yml
  format: yaml
  label: Garner Provider Annotations API
  slug: garner-provider-annotations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-provider-annotations-api-openapi.yml
- filename: garner-providers-api-openapi.yml
  format: yaml
  label: Garner Providers API
  slug: garner-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/garner/openapi/garner-providers-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: The Service may not be used or otherwise provided or made available, either directly or indirectly, (a) in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine, or any other country subject to U.S. trade sanctions
  entity_types:
  - text: Users are only eligible to register for an account and/or use the Service if they are a participating and eligible employee (or eligible dependent of such an employee) of an employer that has separately contracted with Garner
    type: individual
  minimum_age:
    text: By registering to use the Service, you are attesting to the fact that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No medical advice or treatment
    text: The Service is not intended or implied to be a substitute for professional medical diagnosis or treatment.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Garner may delay your registration or take other actions as needed to validate or authenticate your account and eligibility.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Garner
provenance_date: '2026-11-09'
provider_name: Garner
provider_slug: garner
slug: garner-eligibility
source_date: '2026-11-09'
source_filename: garner-eligibility.yml
source_heading: Eligibility
source_page: https://garnerhealth.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Garner\naid: garner\nurl: https://garnerhealth.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: The Service may not be used or otherwise provided or made available, either directly or indirectly, (a)\n    in Cuba, Iran, North Korea, Syria, Crimea region of Ukraine, or any other country subject to U.S. trade sanctions\nentity_types:\n- type: individual\n  text: Users are only eligible to register for an account and/or use the Service if they are a participating and\n    eligible employee (or eligible dependent\
  \ of such an employee) of an employer that has separately contracted\n    with Garner\nrestricted_uses:\n- summary: No medical advice or treatment\n  text: The Service is not intended or implied to be a substitute for professional medical diagnosis or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Garner may delay your registration or take other actions as needed to validate or authenticate your account\n    and eligibility.\nminimum_age:\n  value: '18'\n  text: By registering to use the Service, you are attesting to the fact that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/garner/eligibility/garner-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Garner's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Healthcare
- Provider Data
- Care Navigation
- Health Insurance
- Claims Analytics
- Provider Search
- Doctor Quality
---
