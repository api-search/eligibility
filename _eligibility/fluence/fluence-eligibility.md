---
api_specs:
- filename: fluence-billing-api-openapi.yml
  format: yaml
  label: Fluence Billing API
  slug: fluence-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-billing-api-openapi.yml
- filename: fluence-hardware-api-openapi.yml
  format: yaml
  label: Fluence Hardware API
  slug: fluence-hardware-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-hardware-api-openapi.yml
- filename: fluence-prices-api-openapi.yml
  format: yaml
  label: Fluence Prices API
  slug: fluence-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-prices-api-openapi.yml
- filename: fluence-publicip-api-openapi.yml
  format: yaml
  label: Fluence PublicIP API
  slug: fluence-publicip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-publicip-api-openapi.yml
- filename: fluence-service-api-openapi.yml
  format: yaml
  label: Fluence Service API
  slug: fluence-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-service-api-openapi.yml
- filename: fluence-ssh-keys-api-openapi.yml
  format: yaml
  label: Fluence SSH keys API
  slug: fluence-ssh-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-ssh-keys-api-openapi.yml
- filename: fluence-storage-api-openapi.yml
  format: yaml
  label: Fluence Storage API
  slug: fluence-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-storage-api-openapi.yml
- filename: fluence-subnets-api-openapi.yml
  format: yaml
  label: Fluence Subnets API
  slug: fluence-subnets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-subnets-api-openapi.yml
- filename: fluence-users-api-openapi.yml
  format: yaml
  label: Fluence Users API
  slug: fluence-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-users-api-openapi.yml
- filename: fluence-vms-api-openapi.yml
  format: yaml
  label: Fluence V Ms API
  slug: fluence-vms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-vms-api-openapi.yml
- filename: fluence-vpcs-api-openapi.yml
  format: yaml
  label: Fluence VP Cs API
  slug: fluence-vpcs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-vpcs-api-openapi.yml
- filename: fluence-security-group-api-openapi.yml
  format: yaml
  label: Fluence Security Group API
  slug: fluence-security-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluence/openapi/fluence-security-group-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: 'The Platform may not be used by users residing, located, incorporated, or otherwise organized or established in any of the following, restricted jurisdictions: Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, Luhansk, Kherson and Zaporizhzhia regions of Ukraine'
  entity_types:
  - text: By using the Platform, you agree that you are at least 18 years of age, or if you are under 18 years of age (a “Minor”), that you are using the Platform with the consent of your parent or legal guardian
    type: individual
  - text: If you are an entity, neither you nor any shareholders, owners, or principals are on any applicable sanctions lists.
    type: business
  minimum_age:
    text: you agree that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: AI Model API Service age limit
    text: you must be at least 18 years old to use the AI Model API Service
  - summary: Restricted U.S. states for certain Services
    text: certain Services may not be used by users residing in, located in, incorporated in, or otherwise organized or established in certain jurisdictions within the U.S., including Alaska, Alabama, Colorado
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
name: Fluence
provenance_date: '2026-11-09'
provider_name: Fluence
provider_slug: fluence
slug: fluence-eligibility
source_date: '2026-11-09'
source_filename: fluence-eligibility.yml
source_heading: Eligibility
source_page: https://console.fluence.network/files/FLUENCE_TERMS_OF_SERVICE.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fluence\naid: fluence\nurl: https://console.fluence.network/files/FLUENCE_TERMS_OF_SERVICE.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: 'The Platform may not be used by users residing, located, incorporated, or otherwise organized or established\n    in any of the following, restricted jurisdictions: Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk,\n    Luhansk, Kherson and Zaporizhzhia regions of Ukraine'\nentity_types:\n- type: individual\n  text: By using the Platform, you agree that you are at least 18 years of age, or if you are under\
  \ 18 years of\n    age (a “Minor”), that you are using the Platform with the consent of your parent or legal guardian\n- type: business\n  text: If you are an entity, neither you nor any shareholders, owners, or principals are on any applicable sanctions\n    lists.\nrestricted_uses:\n- summary: AI Model API Service age limit\n  text: you must be at least 18 years old to use the AI Model API Service\n- summary: Restricted U.S. states for certain Services\n  text: certain Services may not be used by users residing in, located in, incorporated in, or otherwise organized\n    or established in certain jurisdictions within the U.S., including Alaska, Alabama, Colorado\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you agree that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/fluence/eligibility/fluence-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Fluence's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web3
- Cloud Compute
- DePIN
- GPU
- Infrastructure
- Virtual Machines
- AI Infrastructure
- Decentralized Cloud
---
