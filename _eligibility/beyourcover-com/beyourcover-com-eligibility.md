---
api_specs:
- filename: beyourcover-com-account-api-openapi.yml
  format: yaml
  label: BeYourCover Account API
  slug: beyourcover-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-account-api-openapi.yml
- filename: beyourcover-com-books-api-openapi.yml
  format: yaml
  label: BeYourCover Books API
  slug: beyourcover-com-books-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-books-api-openapi.yml
- filename: beyourcover-com-clients-api-openapi.yml
  format: yaml
  label: BeYourCover Clients API
  slug: beyourcover-com-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-clients-api-openapi.yml
- filename: beyourcover-com-covers-api-openapi.yml
  format: yaml
  label: BeYourCover Covers API
  slug: beyourcover-com-covers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-covers-api-openapi.yml
- filename: beyourcover-com-jobs-api-openapi.yml
  format: yaml
  label: BeYourCover Jobs API
  slug: beyourcover-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-jobs-api-openapi.yml
- filename: beyourcover-com-service-api-openapi.yml
  format: yaml
  label: BeYourCover Service API
  slug: beyourcover-com-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-service-api-openapi.yml
- filename: beyourcover-com-templates-api-openapi.yml
  format: yaml
  label: BeYourCover Templates API
  slug: beyourcover-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-templates-api-openapi.yml
- filename: beyourcover-com-wraps-api-openapi.yml
  format: yaml
  label: BeYourCover Wraps API
  slug: beyourcover-com-wraps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyourcover-com/openapi/beyourcover-com-wraps-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service on behalf of a company, publisher, agency, or other organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: null
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
name: BeYourCover
provenance_date: '2026-11-09'
provider_name: BeYourCover
provider_slug: beyourcover-com
slug: beyourcover-com-eligibility
source_date: '2026-11-09'
source_filename: beyourcover-com-eligibility.yml
source_heading: Eligibility
source_page: https://beyourcover.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeYourCover\naid: beyourcover-com\nurl: https://beyourcover.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service on behalf of a company, publisher, agency, or other organization, you represent that\n    you have authority to bind that organization to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beyourcover-com/eligibility/beyourcover-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from BeYourCover's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- BookCover
- Design
- Publishing
---
