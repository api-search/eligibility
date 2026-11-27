---
api_specs:
- filename: amazon-ads-openapi-generated.yml
  format: yaml
  label: Amazon Ads API
  slug: amazon-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-ads/openapi/_ae-authored/amazon-ads-openapi-generated.yml
- filename: amazon-ads-activategiftcard-api-openapi.yml
  format: yaml
  label: Amazon Ads Activategiftcard API
  slug: amazon-ads-activategiftcard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-ads/openapi/amazon-ads-activategiftcard-api-openapi.yml
- filename: amazon-ads-activationstatuscheck-api-openapi.yml
  format: yaml
  label: Amazon Ads Activationstatuscheck API
  slug: amazon-ads-activationstatuscheck-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-ads/openapi/amazon-ads-activationstatuscheck-api-openapi.yml
- filename: amazon-ads-amazon-ads-api-api-openapi.yml
  format: yaml
  label: Amazon Ads Amazon Ads API
  slug: amazon-ads-amazon-ads-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-ads/openapi/amazon-ads-amazon-ads-api-api-openapi.yml
- filename: amazon-ads-cancelgiftcard-api-openapi.yml
  format: yaml
  label: Amazon Ads Cancelgiftcard API
  slug: amazon-ads-cancelgiftcard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-ads/openapi/amazon-ads-cancelgiftcard-api-openapi.yml
- filename: amazon-ads-creategiftcard-api-openapi.yml
  format: yaml
  label: Amazon Ads Creategiftcard API
  slug: amazon-ads-creategiftcard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-ads/openapi/amazon-ads-creategiftcard-api-openapi.yml
- filename: amazon-ads-deactivategiftcard-api-openapi.yml
  format: yaml
  label: Amazon Ads Deactivategiftcard API
  slug: amazon-ads-deactivategiftcard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-ads/openapi/amazon-ads-deactivategiftcard-api-openapi.yml
- filename: amazon-ads-getgiftcard-api-openapi.yml
  format: yaml
  label: Amazon Ads Getgiftcard API
  slug: amazon-ads-getgiftcard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-ads/openapi/amazon-ads-getgiftcard-api-openapi.yml
- filename: amazon-ads-install-api-openapi.yml
  format: yaml
  label: Amazon Ads Install API
  slug: amazon-ads-install-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazon-ads/openapi/amazon-ads-install-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you (if registering as an individual)
    type: individual
  - text: the entity you represent (if registering as a business)
    type: business
  minimum_age:
    text: You are at least the legal age of majority and that you are able to form a legally binding contract.
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
name: Amazon Ads
provenance_date: '2026-11-09'
provider_name: Amazon Ads
provider_slug: amazon-ads
slug: amazon-ads-eligibility
source_date: '2026-11-09'
source_filename: amazon-ads-eligibility.yml
source_heading: Eligibility
source_page: https://developer.amazon.com/support/legal/da
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Ads\naid: amazon-ads\nurl: https://developer.amazon.com/support/legal/da\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you (if registering as an individual)\n- type: business\n  text: the entity you represent (if registering as a business)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You are at least the legal age of majority and that you are able to form a legally binding contract.\n"
source_yaml_url: https://artifacts.apis.io/amazon-ads/eligibility/amazon-ads-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Amazon Ads's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Marketing
- Amazon
- Technology
- Software-as-a-Service
---
