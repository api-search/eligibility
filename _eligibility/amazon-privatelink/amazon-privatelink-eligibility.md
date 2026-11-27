---
api_specs:
- filename: amazon-privatelink-endpoint-connections-api-openapi.yml
  format: yaml
  label: Amazon PrivateLink Endpoint Connections API
  slug: amazon-privatelink-endpoint-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-privatelink/openapi/amazon-privatelink-endpoint-connections-api-openapi.yml
- filename: amazon-privatelink-endpoint-services-api-openapi.yml
  format: yaml
  label: Amazon PrivateLink Endpoint Services API
  slug: amazon-privatelink-endpoint-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-privatelink/openapi/amazon-privatelink-endpoint-services-api-openapi.yml
- filename: amazon-privatelink-principals-api-openapi.yml
  format: yaml
  label: Amazon PrivateLink Principals API
  slug: amazon-privatelink-principals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-privatelink/openapi/amazon-privatelink-principals-api-openapi.yml
- filename: amazon-privatelink-vpc-endpoints-api-openapi.yml
  format: yaml
  label: Amazon PrivateLink VPC Endpoints API
  slug: amazon-privatelink-vpc-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-privatelink/openapi/amazon-privatelink-vpc-endpoints-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spend limits not for critical systems
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems, any regulated content (such as protected health information), government data, or any content of government entities.
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
name: Amazon PrivateLink
provenance_date: '2026-11-09'
provider_name: Amazon PrivateLink
provider_slug: amazon-privatelink
slug: amazon-privatelink-eligibility
source_date: '2026-11-09'
source_filename: amazon-privatelink-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon PrivateLink\naid: amazon-privatelink\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spend limits not for critical systems\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems, any regulated content (such as protected health information),\n    government data, or any content of government entities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-privatelink/eligibility/amazon-privatelink-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Amazon PrivateLink's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Networking
- Private Connectivity
- Security
- VPC
- Zero Trust
- Endpoint Services
---
