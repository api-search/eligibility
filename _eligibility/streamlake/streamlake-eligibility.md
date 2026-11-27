---
api_specs:
- filename: streamlake-gateway-api-openapi.yml
  format: yaml
  label: StreamLake Gateway API
  slug: streamlake-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/streamlake/openapi/streamlake-gateway-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    - IN
    - ID
    - AE
    - MX
    text: If you are using our Services in Brazil, the following additional terms apply.
  entity_types:
  - text: refer to the individual accepting this Agreement
    type: individual
  - text: If you are using our Services on behalf of a company, association, partnership, organization or other entity
    type: business
  minimum_age:
    text: Anyone under the age of 13 or other minimum age as defined under applicable laws of your jurisdiction
    value: '13'
  restricted_uses:
  - summary: No commercial use without consent
    text: market, rent or lease the Services for a fee or charge, or use the Services to advertise or perform any commercial solicitation without our written consent
  - summary: No AI model development with Services or outputs
    text: training, or otherwise developing your or any third party’s artificial intelligence or machine learning models
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
name: StreamLake
provenance_date: '2026-11-10'
provider_name: StreamLake
provider_slug: streamlake
slug: streamlake-eligibility
source_date: '2026-11-10'
source_filename: streamlake-eligibility.yml
source_heading: Eligibility
source_page: https://streamlake.ai/document/DOC/mgkchnd89grpt1961fw
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StreamLake\naid: streamlake\nurl: https://streamlake.ai/document/DOC/mgkchnd89grpt1961fw\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  - IN\n  - ID\n  - AE\n  - MX\n  excluded: []\n  text: If you are using our Services in Brazil, the following additional terms apply.\nentity_types:\n- type: individual\n  text: refer to the individual accepting this Agreement\n- type: business\n  text: If you are using our Services on behalf of a company, association, partnership, organization or other entity\nrestricted_uses:\n- summary: No commercial use without consent\n  text: market, rent or lease the Services\
  \ for a fee or charge, or use the Services to advertise or perform any\n    commercial solicitation without our written consent\n- summary: No AI model development with Services or outputs\n  text: training, or otherwise developing your or any third party’s artificial intelligence or machine learning\n    models\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Anyone under the age of 13 or other minimum age as defined under applicable laws of your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/streamlake/eligibility/streamlake-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from StreamLake's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Model Inference
- Chat Completions
- AI Coding
- Kuaishou
---
