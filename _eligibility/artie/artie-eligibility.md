---
api_specs:
- filename: artie-column-hashing-salts-api-openapi.yml
  format: yaml
  label: Artie Column Hashing Salts API
  slug: artie-column-hashing-salts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-column-hashing-salts-api-openapi.yml
- filename: artie-connectors-api-openapi.yml
  format: yaml
  label: Artie Connectors API
  slug: artie-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-connectors-api-openapi.yml
- filename: artie-data-catalog-api-openapi.yml
  format: yaml
  label: Artie Data Catalog API
  slug: artie-data-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-data-catalog-api-openapi.yml
- filename: artie-encryption-keys-api-openapi.yml
  format: yaml
  label: Artie Encryption Keys API
  slug: artie-encryption-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-encryption-keys-api-openapi.yml
- filename: artie-ingestion-api-keys-api-openapi.yml
  format: yaml
  label: Artie Ingestion API Keys API
  slug: artie-ingestion-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-ingestion-api-keys-api-openapi.yml
- filename: artie-pipelines-api-openapi.yml
  format: yaml
  label: Artie Pipelines API
  slug: artie-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-pipelines-api-openapi.yml
- filename: artie-privatelink-connections-api-openapi.yml
  format: yaml
  label: Artie PrivateLink Connections API
  slug: artie-privatelink-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-privatelink-connections-api-openapi.yml
- filename: artie-source-readers-api-openapi.yml
  format: yaml
  label: Artie Source Readers API
  slug: artie-source-readers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-source-readers-api-openapi.yml
- filename: artie-ssh-tunnels-api-openapi.yml
  format: yaml
  label: Artie SSH Tunnels API
  slug: artie-ssh-tunnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-ssh-tunnels-api-openapi.yml
- filename: artie-artie-api-api-openapi.yml
  format: yaml
  label: Artie API
  slug: artie-artie-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-artie-api-api-openapi.yml
- filename: artie-company-api-openapi.yml
  format: yaml
  label: Artie Company API
  slug: artie-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-company-api-openapi.yml
- filename: artie-kafka-clusters-api-openapi.yml
  format: yaml
  label: Artie Kafka Clusters API
  slug: artie-kafka-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artie/openapi/artie-kafka-clusters-api-openapi.yml
claim_count: 5
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
    text: Customer may not access the Artie Services if Customer is located in a territory where U.S. businesses are prohibited from engaging in business (such as Cuba, Iran, North Korea, Sudan, Syria)
  entity_types:
  - text: that the Customer, if an individual, is at least 18 years of age
    type: individual
  - text: If you are accessing or using the Artie Services on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  minimum_age:
    text: that the Customer, if an individual, is at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Regulated data
    text: does not contain any data subject to special regulatory regimes (such as HIPAA, PCI-DSS, ITAR, etc.), unless expressly agreed in writing by Artie
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
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
name: Artie
provenance_date: '2026-11-09'
provider_name: Artie
provider_slug: artie
slug: artie-eligibility
source_date: '2026-11-09'
source_filename: artie-eligibility.yml
source_heading: Eligibility
source_page: https://www.artie.com/docs/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Artie\naid: artie\nurl: https://www.artie.com/docs/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer may not access the Artie Services if Customer is located in a territory where U.S. businesses are\n    prohibited from engaging in business (such as Cuba, Iran, North Korea, Sudan, Syria)\nentity_types:\n- type: individual\n  text: that the Customer, if an individual, is at least 18 years of age\n- type: business\n  text: If you are accessing or using the Artie Services on behalf of your company, you represent that\
  \ you are authorized\n    to accept this Agreement on behalf of your company\nrestricted_uses:\n- summary: Regulated data\n  text: does not contain any data subject to special regulatory regimes (such as HIPAA, PCI-DSS, ITAR, etc.), unless\n    expressly agreed in writing by Artie\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: that the Customer, if an individual, is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/artie/eligibility/artie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Artie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Replication
- Change Data Capture
- Data Integration
- ETL
- Streaming
- Database
- Data Warehouse
- Data Engineering
---
