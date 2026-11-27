---
api_specs:
- filename: airbyte-airbyte-marketing-site-api-openapi.yml
  format: yaml
  label: Airbyte Airbyte Marketing Site API
  slug: airbyte-airbyte-marketing-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airbyte/openapi/airbyte-airbyte-marketing-site-api-openapi.yml
- filename: airbyte-well-known-api-openapi.yml
  format: yaml
  label: Airbyte .well Known API
  slug: airbyte-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airbyte/openapi/airbyte-well-known-api-openapi.yml
- filename: airbyte-x402-api-openapi.yml
  format: yaml
  label: Airbyte X402 API
  slug: airbyte-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airbyte/openapi/airbyte-x402-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Customer may not access the Airbyte Hosted Services if Customer is located in a territory where U.S. businesses are prohibited from engaging in business (such as Cuba, Iran, North Korea, Sudan, or Syria)
  entity_types:
  - text: The Customer, if an individual, is at least 18 years of age
    type: individual
  - text: If you are accessing or using the Airbyte Hosted Services on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  minimum_age:
    text: that the Customer, if an individual, is at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Special regulated data
    text: Customer shall not integrate any Special Data to the Airbyte Hosted Services if Customer determines that such technical and organizational measures are insufficient to protect Special Data in accordance with applicable laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer will need to register and create an account
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Airbyte
provenance_date: '2026-11-09'
provider_name: Airbyte
provider_slug: airbyte
slug: airbyte-eligibility
source_date: '2026-11-09'
source_filename: airbyte-eligibility.yml
source_heading: Eligibility
source_page: https://airbyte.com/company/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airbyte\naid: airbyte\nurl: https://airbyte.com/company/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer may not access the Airbyte Hosted Services if Customer is located in a territory where U.S. businesses\n    are prohibited from engaging in business (such as Cuba, Iran, North Korea, Sudan, or Syria)\nentity_types:\n- type: individual\n  text: The Customer, if an individual, is at least 18 years of age\n- type: business\n  text: If you are accessing or using the Airbyte Hosted Services on behalf of your company, you represent\
  \ that\n    you are authorized to accept this Agreement on behalf of your company\nrestricted_uses:\n- summary: Special regulated data\n  text: Customer shall not integrate any Special Data to the Airbyte Hosted Services if Customer determines that\n    such technical and organizational measures are insufficient to protect Special Data in accordance with applicable\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer will need to register and create an account\nminimum_age:\n  value: '18'\n  text: that the Customer, if an individual, is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/airbyte/eligibility/airbyte-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Airbyte's own page on 2026-11-09.
synthetic: false
tags:
- Data Integration
- ETL
- ELT
- Open Source
- Data Pipeline
- Connectors
- Data
---
