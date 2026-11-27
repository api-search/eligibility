---
api_specs:
- filename: amazon-license-manager-license-configurations-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Configurations API
  slug: amazon-license-manager-license-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-license-configurations-api-openapi.yml
- filename: amazon-license-manager-grant-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager Grant API
  slug: amazon-license-manager-grant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-grant-api-openapi.yml
- filename: amazon-license-manager-license-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager License API
  slug: amazon-license-manager-license-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-license-api-openapi.yml
- filename: amazon-license-manager-license-asset-group-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager License Asset Group API
  slug: amazon-license-manager-license-asset-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-license-asset-group-api-openapi.yml
- filename: amazon-license-manager-license-asset-ruleset-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager License Asset Ruleset API
  slug: amazon-license-manager-license-asset-ruleset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-license-asset-ruleset-api-openapi.yml
- filename: amazon-license-manager-license-conversion-task-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager License Conversion Task API
  slug: amazon-license-manager-license-conversion-task-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-license-conversion-task-api-openapi.yml
- filename: amazon-license-manager-license-manager-report-generator-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager License Manager Report Generator API
  slug: amazon-license-manager-license-manager-report-generator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-license-manager-report-generator-api-openapi.yml
- filename: amazon-license-manager-operations-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager Operations API
  slug: amazon-license-manager-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-operations-api-openapi.yml
- filename: amazon-license-manager-token-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager Token API
  slug: amazon-license-manager-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-token-api-openapi.yml
- filename: amazon-license-manager-identity-provider-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager Identity Provider API
  slug: amazon-license-manager-identity-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-identity-provider-api-openapi.yml
- filename: amazon-license-manager-license-server-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager License Server API
  slug: amazon-license-manager-license-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-license-server-api-openapi.yml
- filename: amazon-license-manager-subscription-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager Subscription API
  slug: amazon-license-manager-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-subscription-api-openapi.yml
- filename: amazon-license-manager-user-api-openapi.yml
  format: yaml
  label: Amazon License Manager License Manager User API
  slug: amazon-license-manager-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-license-manager/openapi/amazon-license-manager-user-api-openapi.yml
claim_count: 2
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
  - summary: High-risk use of Microsoft Software
    text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical equipment, motor vehicles, weaponry systems, or any similar scenario
  - summary: Spend limits not for critical systems
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems
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
name: Amazon License Manager
provenance_date: '2026-11-09'
provider_name: Amazon License Manager
provider_slug: amazon-license-manager
slug: amazon-license-manager-eligibility
source_date: '2026-11-09'
source_filename: amazon-license-manager-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon License Manager\naid: amazon-license-manager\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk use of Microsoft Software\n  text: You are not granted any right to use the Microsoft Software in any application controlling aircraft or other\n    modes of human mass transportation, nuclear or chemical facilities, life support systems, implantable medical\n    equipment, motor vehicles, weaponry systems, or any similar scenario\n- summary: Spend limits not\
  \ for critical systems\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amazon-license-manager/eligibility/amazon-license-manager-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Amazon License Manager's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- Compliance
- Cost Management
- License Management
- Software Licensing
---
