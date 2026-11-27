---
api_specs:
- filename: localclarity-endpoints-api-openapi.yml
  format: yaml
  label: LocalClarity Endpoints API
  slug: localclarity-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/localclarity/openapi/localclarity-endpoints-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Subscription Service if you are legally prohibited from receiving or using the Subscription Service under the laws of the country in which you are resident or from which you access or use the Subscription Service.
  entity_types:
  - text: whether personally or on behalf of an entity (“Customer” or “you”)
    type: individual
  - text: whether personally or on behalf of an entity (“Customer” or “you”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive information
    text: YOU AGREE NOT TO USE THE SUBSCRIPTION SERVICE TO COLLECT, MANAGE OR PROCESS SENSITIVE INFORMATION.
  - summary: Not for HIPAA/GLBA/FISMA-regulated communications
    text: The Subscription Service is not designed to comply with industry-specific regulations such as the Health Insurance Portability and Accountability Act (HIPAA), the Gramm-Leach-Bliley Act (GLBA), or the Federal Information Security Management Act (FISMA), so you may not use the Subscription Service where your communications would be subject to such laws.
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
name: LocalClarity
provenance_date: '2026-11-09'
provider_name: LocalClarity
provider_slug: localclarity
slug: localclarity-eligibility
source_date: '2026-11-09'
source_filename: localclarity-eligibility.yml
source_heading: Eligibility
source_page: https://www.localclarity.com/terms/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LocalClarity\naid: localclarity\nurl: https://www.localclarity.com/terms/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Subscription Service if you are legally prohibited from receiving or using the Subscription\n    Service under the laws of the country in which you are resident or from which you access or use the Subscription\n    Service.\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (“Customer” or “you”)\n- type: business\n  text: whether personally or on behalf of an entity (“Customer” or “you”)\n\
  restricted_uses:\n- summary: No sensitive information\n  text: YOU AGREE NOT TO USE THE SUBSCRIPTION SERVICE TO COLLECT, MANAGE OR PROCESS SENSITIVE INFORMATION.\n- summary: Not for HIPAA/GLBA/FISMA-regulated communications\n  text: The Subscription Service is not designed to comply with industry-specific regulations such as the Health\n    Insurance Portability and Accountability Act (HIPAA), the Gramm-Leach-Bliley Act (GLBA), or the Federal Information\n    Security Management Act (FISMA), so you may not use the Subscription Service where your communications would\n    be subject to such laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/localclarity/eligibility/localclarity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from LocalClarity's own page on 2026-11-09.
synthetic: false
tags:
- Local SEO
- Google Business Profile
- Review Management
- Local Search
- Listings Management
- Reputation Management
- Local Marketing
- Business Listings
- Location Data
- Sentiment Analysis
- Multi-Location Brands
- Marketing
---
