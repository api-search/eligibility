---
api_specs:
- filename: goodlord-agent-api-openapi.yml
  format: yaml
  label: Goodlord Agent API
  slug: goodlord-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-agent-api-openapi.yml
- filename: goodlord-application-api-openapi.yml
  format: yaml
  label: Goodlord Application API
  slug: goodlord-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-application-api-openapi.yml
- filename: goodlord-authentication-api-openapi.yml
  format: yaml
  label: Goodlord Authentication API
  slug: goodlord-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-authentication-api-openapi.yml
- filename: goodlord-company-api-openapi.yml
  format: yaml
  label: Goodlord Company API
  slug: goodlord-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-company-api-openapi.yml
- filename: goodlord-file-api-openapi.yml
  format: yaml
  label: Goodlord File API
  slug: goodlord-file-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-file-api-openapi.yml
- filename: goodlord-insuranceclaim-api-openapi.yml
  format: yaml
  label: Goodlord Insurance Claim API
  slug: goodlord-insuranceclaim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-insuranceclaim-api-openapi.yml
- filename: goodlord-media-api-openapi.yml
  format: yaml
  label: Goodlord Media API
  slug: goodlord-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-media-api-openapi.yml
- filename: goodlord-payment-api-openapi.yml
  format: yaml
  label: Goodlord Payment API
  slug: goodlord-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-payment-api-openapi.yml
- filename: goodlord-rentschedule-api-openapi.yml
  format: yaml
  label: Goodlord Rent Schedule API
  slug: goodlord-rentschedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-rentschedule-api-openapi.yml
- filename: goodlord-rentschedulerow-api-openapi.yml
  format: yaml
  label: Goodlord Rent Schedule Row API
  slug: goodlord-rentschedulerow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-rentschedulerow-api-openapi.yml
- filename: goodlord-rentschedulerowpostdto-api-openapi.yml
  format: yaml
  label: Goodlord Rent Schedule Row Post Dto API
  slug: goodlord-rentschedulerowpostdto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-rentschedulerowpostdto-api-openapi.yml
- filename: goodlord-rentschedulerowupdate-api-openapi.yml
  format: yaml
  label: Goodlord Rent Schedule Row Update API
  slug: goodlord-rentschedulerowupdate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-rentschedulerowupdate-api-openapi.yml
- filename: goodlord-role-api-openapi.yml
  format: yaml
  label: Goodlord Role API
  slug: goodlord-role-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-role-api-openapi.yml
- filename: goodlord-rolegroup-api-openapi.yml
  format: yaml
  label: Goodlord Role Group API
  slug: goodlord-rolegroup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-rolegroup-api-openapi.yml
- filename: goodlord-subject-api-openapi.yml
  format: yaml
  label: Goodlord Subject API
  slug: goodlord-subject-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goodlord/openapi/goodlord-subject-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Goodlord reserves the right to limit, in its sole discretion, the provision and quantity of any feature, product or service to any person or geographic area.
  minimum_age:
    text: where applicable representing that you are of sufficient legal age to use or participate in such service or feature
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited purposes
    text: You may not use the Site or any Content for any purpose that is unlawful or prohibited by these Terms of Use
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
name: Goodlord
provenance_date: '2026-11-09'
provider_name: Goodlord
provider_slug: goodlord
slug: goodlord-eligibility
source_date: '2026-11-09'
source_filename: goodlord-eligibility.yml
source_heading: Eligibility
source_page: https://www.goodlord.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goodlord\naid: goodlord\nurl: https://www.goodlord.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Goodlord reserves the right to limit, in its sole discretion, the provision and quantity of any feature,\n    product or service to any person or geographic area.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited purposes\n  text: You may not use the Site or any Content for any purpose that is unlawful or prohibited by these Terms of\n    Use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: where applicable representing that you are of sufficient legal age to use or participate in such service\n    or feature\n"
source_yaml_url: https://artifacts.apis.io/goodlord/eligibility/goodlord-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Goodlord's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- United Kingdom
- PropTech
- Property Management
- Rentals
- Lettings
- Tenant Referencing
- Tenancy Management
- Insurance
- Payments
---
