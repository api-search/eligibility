---
api_specs:
- filename: australia-post-endpoints-api-openapi.yml
  format: yaml
  label: Australia Post Endpoints API
  slug: australia-post-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/australia-post/openapi/australia-post-endpoints-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: makes available to businesses and other customers
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use only to facilitate Australia Post services
    text: must only use the APIs and the Access Credentials to facilitate the provision of our services (principally deliveries, postage transactions and certain financial services)
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
name: Australia Post
provenance_date: '2026-11-09'
provider_name: Australia Post
provider_slug: australia-post
slug: australia-post-eligibility
source_date: '2026-11-09'
source_filename: australia-post-eligibility.yml
source_heading: Eligibility
source_page: https://auspost.com.au/content/dam/auspost_corp/media/documents/api-licence-terms-of-use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Australia Post\naid: australia-post\nurl: https://auspost.com.au/content/dam/auspost_corp/media/documents/api-licence-terms-of-use.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: makes available to businesses and other customers\nrestricted_uses:\n- summary: Use only to facilitate Australia Post services\n  text: must only use the APIs and the Access Credentials to facilitate the provision of our services (principally\n    deliveries, postage transactions and certain financial services)\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/australia-post/eligibility/australia-post-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Australia Post's own page on 2026-11-09.
synthetic: false
tags:
- Address Validation
- Click and Collect
- Delivery
- E-Commerce
- Labels
- Location
- Logistics
- Parcel Locker
- Postal
- Postage
- Shipping
- Tracking
- Australia
---
