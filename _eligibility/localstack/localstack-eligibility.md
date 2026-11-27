---
api_specs:
- filename: localstack-aws-api-openapi.yml
  format: yaml
  label: LocalStack Aws API
  slug: localstack-aws-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localstack/openapi/localstack-aws-api-openapi.yml
- filename: localstack-localstack-api-openapi.yml
  format: yaml
  label: LocalStack API
  slug: localstack-localstack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localstack/openapi/localstack-localstack-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not use the Software or Service by any individual or entity in any country to which the United States has embargoed goods.
  entity_types:
  - text: IF AN INDIVIDUAL IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, SUCH PERSON REPRESENTS AND WARRANTS THAT IT HAS THE LEGAL AUTHORITY TO BIND SUCH LEGAL ENTITY
    type: business
  minimum_age:
    text: THE LOCALSTACK ASSETS ARE INTENDED FOR THE CUSTOMER AND ITS AUTHORIZED USERS ONLY AND ARE NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE.
    value: '13'
  restricted_uses:
  - summary: Non-Production use only
    text: solely for Customer’s Non-Production, internal business operations
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
name: LocalStack
provenance_date: '2026-11-09'
provider_name: LocalStack
provider_slug: localstack
slug: localstack-eligibility
source_date: '2026-11-09'
source_filename: localstack-eligibility.yml
source_heading: Eligibility
source_page: https://www.localstack.cloud/legal/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LocalStack\naid: localstack\nurl: https://www.localstack.cloud/legal/msa\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not use the Software or Service by any individual or entity in any country to which the United\n    States has embargoed goods.\nentity_types:\n- type: business\n  text: IF AN INDIVIDUAL IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A LEGAL ENTITY, SUCH PERSON REPRESENTS AND\n    WARRANTS THAT IT HAS THE LEGAL AUTHORITY TO BIND SUCH LEGAL ENTITY\nrestricted_uses:\n- summary: Non-Production use only\n  text: solely for Customer’s Non-Production, internal\
  \ business operations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: THE LOCALSTACK ASSETS ARE INTENDED FOR THE CUSTOMER AND ITS AUTHORIZED USERS ONLY AND ARE NOT FOR USE BY\n    CHILDREN UNDER 13 YEARS OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/localstack/eligibility/localstack-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LocalStack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Cloud
- Amazon Web Services
- Emulator
- Testing
- DevOps
- Serverless
- Infrastructure
---
