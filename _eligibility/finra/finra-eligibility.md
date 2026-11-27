---
api_specs:
- filename: finra-async-api-openapi.yml
  format: yaml
  label: FINRA Async API
  slug: finra-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-async-api-openapi.yml
- filename: finra-datasets-api-openapi.yml
  format: yaml
  label: FINRA Datasets API
  slug: finra-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-datasets-api-openapi.yml
- filename: finra-metadata-api-openapi.yml
  format: yaml
  label: FINRA Metadata API
  slug: finra-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-metadata-api-openapi.yml
- filename: finra-partitions-api-openapi.yml
  format: yaml
  label: FINRA Partitions API
  slug: finra-partitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-partitions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Developer is a Legal Entity, Developer represents and warrants that (a) it is duly organized and in good standing under the Laws of the jurisdiction of its organization
    type: business
  - text: the individual accepting these Terms, when they accept it on their own behalf
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competing services and misuse
    text: use the Licensed Materials to create any algorithm, product, or service that competes with FINRA’s products or services
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
name: FINRA
provenance_date: '2026-11-09'
provider_name: FINRA
provider_slug: finra
slug: finra-eligibility
source_date: '2026-11-09'
source_filename: finra-eligibility.yml
source_heading: Eligibility
source_page: https://developer.finra.org/finra-api-terms-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FINRA\naid: finra\nurl: https://developer.finra.org/finra-api-terms-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If Developer is a Legal Entity, Developer represents and warrants that (a) it is duly organized and in good\n    standing under the Laws of the jurisdiction of its organization\n- type: individual\n  text: the individual accepting these Terms, when they accept it on their own behalf\nrestricted_uses:\n- summary: Competing services and misuse\n  text: use the Licensed Materials to create any algorithm, product, or\
  \ service that competes with FINRA’s products\n    or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/finra/eligibility/finra-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from FINRA's own page on 2026-11-09.
synthetic: false
tags:
- Compliance
- Finance
- Regulations
- Securities
- Market Data
---
