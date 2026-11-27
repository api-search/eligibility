---
api_specs:
- filename: soveren-assets-api-openapi.yml
  format: yaml
  label: Soveren Assets API
  slug: soveren-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soveren/openapi/soveren-assets-api-openapi.yml
- filename: soveren-data-types-api-openapi.yml
  format: yaml
  label: Soveren Data Types API
  slug: soveren-data-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soveren/openapi/soveren-data-types-api-openapi.yml
- filename: soveren-endpoints-api-openapi.yml
  format: yaml
  label: Soveren Endpoints API
  slug: soveren-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soveren/openapi/soveren-endpoints-api-openapi.yml
- filename: soveren-kafka-api-openapi.yml
  format: yaml
  label: Soveren Kafka API
  slug: soveren-kafka-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soveren/openapi/soveren-kafka-api-openapi.yml
- filename: soveren-s3-api-openapi.yml
  format: yaml
  label: Soveren S3 API
  slug: soveren-s3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soveren/openapi/soveren-s3-api-openapi.yml
- filename: soveren-sql-db-api-openapi.yml
  format: yaml
  label: Soveren SQL DB API
  slug: soveren-sql-db-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soveren/openapi/soveren-sql-db-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you access the Website or use any of the Services on behalf of a business (whether registered or operating without registration), that business hereby accepts these Terms.
    type: business
  minimum_age:
    text: you are of sufficient age to access the Website and to use the Website and the Services in accordance with the laws and regulations of your country of residence
    value: null
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
name: Soveren
provenance_date: '2026-11-10'
provider_name: Soveren
provider_slug: soveren
slug: soveren-eligibility
source_date: '2026-11-10'
source_filename: soveren-eligibility.yml
source_heading: Eligibility
source_page: https://assets.website-files.com/60ebf6ae3b0fe3c5e739324f/60ebf6ae3b0fe306a53933ce_Soveren_Website_Terms_of_Use_20102020.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Soveren\naid: soveren\nurl: https://assets.website-files.com/60ebf6ae3b0fe3c5e739324f/60ebf6ae3b0fe306a53933ce_Soveren_Website_Terms_of_Use_20102020.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you access the Website or use any of the Services on behalf of a business (whether registered or operating\n    without registration), that business hereby accepts these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of sufficient\
  \ age to access the Website and to use the Website and the Services in accordance with\n    the laws and regulations of your country of residence\n"
source_yaml_url: https://artifacts.apis.io/soveren/eligibility/soveren-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Soveren's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infra Devtools
- Data Security
- DSPM
- DDR
- Privacy
- Kubernetes
- Compliance
- Security
---
