---
api_specs:
- filename: sellfy-content-api-openapi.yml
  format: yaml
  label: Sellfy Content API
  slug: sellfy-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sellfy/openapi/sellfy-content-api-openapi.yml
- filename: sellfy-discovery-api-openapi.yml
  format: yaml
  label: Sellfy Discovery API
  slug: sellfy-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sellfy/openapi/sellfy-discovery-api-openapi.yml
- filename: sellfy-feeds-api-openapi.yml
  format: yaml
  label: Sellfy Feeds API
  slug: sellfy-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sellfy/openapi/sellfy-feeds-api-openapi.yml
- filename: sellfy-licenses-api-openapi.yml
  format: yaml
  label: Sellfy Licenses API
  slug: sellfy-licenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sellfy/openapi/sellfy-licenses-api-openapi.yml
- filename: sellfy-ping-api-openapi.yml
  format: yaml
  label: Sellfy Ping API
  slug: sellfy-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sellfy/openapi/sellfy-ping-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms are business to business contract, and the customer law shall not apply to these Terms and any relations between the User and Sellfy.
    type: business
  - text: You are at least eighteen (18) years old, unless the law applicable to You establishes other age of majority.
    type: individual
  minimum_age:
    text: You are at least eighteen (18) years old, unless the law applicable to You establishes other age of majority.
    value: '18'
  restricted_uses:
  - summary: Illegal use of the Site
    text: The User shall not use the Site for any purpose and in any way that is illegal in accordance with the law applicable to these Terms and your home law or prohibited by these Terms.
  - summary: Nudity and pornography
    text: Any material that includes nudity and pornography
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
name: Sellfy
provenance_date: '2026-11-10'
provider_name: Sellfy
provider_slug: sellfy
slug: sellfy-eligibility
source_date: '2026-11-10'
source_filename: sellfy-eligibility.yml
source_heading: Eligibility
source_page: https://sellfy.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sellfy\naid: sellfy\nurl: https://sellfy.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Terms are business to business contract, and the customer law shall not apply to these Terms and any\n    relations between the User and Sellfy.\n- type: individual\n  text: You are at least eighteen (18) years old, unless the law applicable to You establishes other age of majority.\nrestricted_uses:\n- summary: Illegal use of the Site\n  text: The User shall not use the Site for any purpose and in any way that is illegal in accordance\
  \ with the law\n    applicable to these Terms and your home law or prohibited by these Terms.\n- summary: Nudity and pornography\n  text: Any material that includes nudity and pornography\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least eighteen (18) years old, unless the law applicable to You establishes other age of majority.\n"
source_yaml_url: https://artifacts.apis.io/sellfy/eligibility/sellfy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Sellfy's own page on 2026-11-10.
synthetic: false
tags:
- E-Commerce
- Digital Products
- Software-as-a-Service
- Payments
- Creators
---
