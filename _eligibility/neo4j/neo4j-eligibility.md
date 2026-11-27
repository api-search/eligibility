---
api_specs:
- filename: neo4j-query-api-openapi.yml
  format: yaml
  label: Neo4j Query API
  slug: query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-query-api-openapi.yml
- filename: neo4j-authentication-api-openapi.yml
  format: yaml
  label: Neo4j Authentication API
  slug: neo4j-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-authentication-api-openapi.yml
- filename: neo4j-discovery-api-openapi.yml
  format: yaml
  label: Neo4j Discovery API
  slug: neo4j-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-discovery-api-openapi.yml
- filename: neo4j-instances-api-openapi.yml
  format: yaml
  label: Neo4j Instances API
  slug: neo4j-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-instances-api-openapi.yml
- filename: neo4j-snapshots-api-openapi.yml
  format: yaml
  label: Neo4j Snapshots API
  slug: neo4j-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-snapshots-api-openapi.yml
- filename: neo4j-tenants-api-openapi.yml
  format: yaml
  label: Neo4j Tenants API
  slug: neo4j-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-tenants-api-openapi.yml
- filename: neo4j-transactions-api-openapi.yml
  format: yaml
  label: Neo4j Transactions API
  slug: neo4j-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neo4j/openapi/neo4j-transactions-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Our Site(s) and Products are not intended for children under the age of 16.
    value: '16'
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
name: Neo4j
provenance_date: '2026-11-10'
provider_name: Neo4j
provider_slug: neo4j
slug: neo4j-eligibility
source_date: '2026-11-10'
source_filename: neo4j-eligibility.yml
source_heading: Eligibility
source_page: https://neo4j.com/legal-terms/privacy-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Neo4j\naid: neo4j\nurl: https://neo4j.com/legal-terms/privacy-notice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Our Site(s) and Products are not intended for children under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/neo4j/eligibility/neo4j-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Neo4j's own page on 2026-11-10.
synthetic: false
tags:
- Neo4j
- Graph Database
- Cypher
- Cloud
- GraphQL
- Drivers
- Database
---
