---
api_specs:
- filename: phala-apps-api-openapi.yml
  format: yaml
  label: Phala Network Apps API
  slug: phala-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-apps-api-openapi.yml
- filename: phala-apps-kms-info-api-openapi.yml
  format: yaml
  label: Phala Network Apps Kms Info API
  slug: phala-apps-kms-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-apps-kms-info-api-openapi.yml
- filename: phala-apps-pending-updates-api-openapi.yml
  format: yaml
  label: Phala Network Apps Pending Updates API
  slug: phala-apps-pending-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-apps-pending-updates-api-openapi.yml
- filename: phala-attestations-api-openapi.yml
  format: yaml
  label: Phala Network Attestations API
  slug: phala-attestations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-attestations-api-openapi.yml
- filename: phala-cvms-api-openapi.yml
  format: yaml
  label: Phala Network CVMs API
  slug: phala-cvms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-cvms-api-openapi.yml
- filename: phala-cvms-network-config-api-openapi.yml
  format: yaml
  label: Phala Network Cvms Network Config API
  slug: phala-cvms-network-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-cvms-network-config-api-openapi.yml
- filename: phala-instance-types-api-openapi.yml
  format: yaml
  label: Phala Network Instance Types API
  slug: phala-instance-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-instance-types-api-openapi.yml
- filename: phala-kms-api-openapi.yml
  format: yaml
  label: Phala Network KMS API
  slug: phala-kms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-kms-api-openapi.yml
- filename: phala-ssh-keys-api-openapi.yml
  format: yaml
  label: Phala Network SSH Keys API
  slug: phala-ssh-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-ssh-keys-api-openapi.yml
- filename: phala-webhooks-api-openapi.yml
  format: yaml
  label: Phala Network Webhooks API
  slug: phala-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phala/openapi/phala-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Services, you represent and warrant that you are at least 18 years of age and possess the legal right and ability to enter into binding agreements.
    type: individual
  - text: If you are using the Services on behalf of an entity, you represent that you have authority to bind that entity and that such entity accepts full responsibility for compliance with these Terms.
    type: business
  minimum_age:
    text: you represent and warrant that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Cryptocurrency mining and reward workloads
    text: Use the Services to engage in any form of cryptocurrency mining or compute workloads primarily intended to earn external tokens, credits, or financial incentives from third-party networks
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
name: Phala Network
provenance_date: '2026-11-10'
provider_name: Phala Network
provider_slug: phala
slug: phala-eligibility
source_date: '2026-11-10'
source_filename: phala-eligibility.yml
source_heading: Eligibility
source_page: https://phala.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phala Network\naid: phala\nurl: https://phala.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Services, you represent and warrant that you are at least 18 years of age and possess the legal\n    right and ability to enter into binding agreements.\n- type: business\n  text: If you are using the Services on behalf of an entity, you represent that you have authority to bind that\n    entity and that such entity accepts full responsibility for compliance with these Terms.\nrestricted_uses:\n- summary: Cryptocurrency\
  \ mining and reward workloads\n  text: Use the Services to engage in any form of cryptocurrency mining or compute workloads primarily intended\n    to earn external tokens, credits, or financial incentives from third-party networks\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/phala/eligibility/phala-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Phala Network's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Confidential Computing
- Trusted Execution Environments
- Inference
- Cloud Infrastructure
- Attestation
- LLM Router
---
