---
api_specs:
- filename: vast-ai-accounts-api-openapi.yml
  format: yaml
  label: Vast.ai Accounts API
  slug: vast-ai-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-accounts-api-openapi.yml
- filename: vast-ai-billing-api-openapi.yml
  format: yaml
  label: Vast.ai Billing API
  slug: vast-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-billing-api-openapi.yml
- filename: vast-ai-instances-api-openapi.yml
  format: yaml
  label: Vast.ai Instances API
  slug: vast-ai-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-instances-api-openapi.yml
- filename: vast-ai-machines-api-openapi.yml
  format: yaml
  label: Vast.ai Machines API
  slug: vast-ai-machines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-machines-api-openapi.yml
- filename: vast-ai-network-volumes-api-openapi.yml
  format: yaml
  label: Vast.ai Network Volumes API
  slug: vast-ai-network-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-network-volumes-api-openapi.yml
- filename: vast-ai-search-api-openapi.yml
  format: yaml
  label: Vast.ai Search API
  slug: vast-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-search-api-openapi.yml
- filename: vast-ai-serverless-api-openapi.yml
  format: yaml
  label: Vast.ai Serverless API
  slug: vast-ai-serverless-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-serverless-api-openapi.yml
- filename: vast-ai-team-api-openapi.yml
  format: yaml
  label: Vast.ai Team API
  slug: vast-ai-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-team-api-openapi.yml
- filename: vast-ai-templates-api-openapi.yml
  format: yaml
  label: Vast.ai Templates API
  slug: vast-ai-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-templates-api-openapi.yml
- filename: vast-ai-volumes-api-openapi.yml
  format: yaml
  label: Vast.ai Volumes API
  slug: vast-ai-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vast-ai/openapi/vast-ai-volumes-api-openapi.yml
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
    text: User represents that neither it nor any end users of the Services is (i) located in, organized under the laws of, or ordinarily resident in Cuba, Iran, North Korea, Syria, or the Crimea, Donetsk, Luhansk, Kherson or Zaporizhzhia regions of Ukraine
  entity_types:
  - text: whether personally or on behalf of an entity or Authorized Users
    type: business
  minimum_age:
    text: Persons under the age of 13 are not permitted to register for the Website or use the Company Services.
    value: '13'
  restricted_uses:
  - summary: Cryptocurrency mining on credit-card purchases
    text: you may not engage in any cryptocurrency mining, including but not limited to Bitcoin mining, Ethereum mining, or any other form of digital currency mining.
  - summary: Military or restricted end-uses under export rules
    text: nor use the Services for any end-use restricted under the EAR (e.g., nuclear, missile, chemical or biological weapons, or military end-use in China/Russia) without first obtaining all required government authorizations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
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
name: Vast.ai
provenance_date: '2026-11-10'
provider_name: Vast.ai
provider_slug: vast-ai
slug: vast-ai-eligibility
source_date: '2026-11-10'
source_filename: vast-ai-eligibility.yml
source_heading: Eligibility
source_page: https://vast.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vast.ai\naid: vast-ai\nurl: https://vast.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: User represents that neither it nor any end users of the Services is (i) located in, organized under the\n    laws of, or ordinarily resident in Cuba, Iran, North Korea, Syria, or the Crimea, Donetsk, Luhansk, Kherson\n    or Zaporizhzhia regions of Ukraine\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity or Authorized Users\nrestricted_uses:\n- summary: Cryptocurrency mining on credit-card purchases\n  text: you may\
  \ not engage in any cryptocurrency mining, including but not limited to Bitcoin mining, Ethereum mining,\n    or any other form of digital currency mining.\n- summary: Military or restricted end-uses under export rules\n  text: nor use the Services for any end-use restricted under the EAR (e.g., nuclear, missile, chemical or biological\n    weapons, or military end-use in China/Russia) without first obtaining all required government authorizations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Persons under the age of 13 are not permitted to register for the Website or use the Company Services.\n"
source_yaml_url: https://artifacts.apis.io/vast-ai/eligibility/vast-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vast.ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Cloud
- Compute
- GPU
- Machine Learning
- Marketplace
- Serverless
---
