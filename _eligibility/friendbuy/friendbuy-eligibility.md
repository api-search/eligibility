---
api_specs:
- filename: friendbuy-analytics-api-openapi.yml
  format: yaml
  label: Friendbuy Analytics API
  slug: friendbuy-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-analytics-api-openapi.yml
- filename: friendbuy-authorization-api-openapi.yml
  format: yaml
  label: Friendbuy Authorization API
  slug: friendbuy-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-authorization-api-openapi.yml
- filename: friendbuy-customers-api-openapi.yml
  format: yaml
  label: Friendbuy Customers API
  slug: friendbuy-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-customers-api-openapi.yml
- filename: friendbuy-events-api-openapi.yml
  format: yaml
  label: Friendbuy Events API
  slug: friendbuy-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-events-api-openapi.yml
- filename: friendbuy-management-api-openapi.yml
  format: yaml
  label: Friendbuy Management API
  slug: friendbuy-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-management-api-openapi.yml
- filename: friendbuy-referrals-api-openapi.yml
  format: yaml
  label: Friendbuy Referrals API
  slug: friendbuy-referrals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-referrals-api-openapi.yml
- filename: friendbuy-rewards-loyalty-api-openapi.yml
  format: yaml
  label: Friendbuy Rewards & Loyalty API
  slug: friendbuy-rewards-loyalty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/friendbuy/openapi/friendbuy-rewards-loyalty-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Friendbuy provides services for businesses to acquire new customers and monetize content
    type: business
  minimum_age:
    text: Register for any account if you are under 13 years.
    value: '13'
  restricted_uses:
  - summary: No false information or defamatory content
    text: Give us any false or misleading information in connection with your use of the Service.
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
name: Friendbuy
provenance_date: '2026-11-09'
provider_name: Friendbuy
provider_slug: friendbuy
slug: friendbuy-eligibility
source_date: '2026-11-09'
source_filename: friendbuy-eligibility.yml
source_heading: Eligibility
source_page: https://www.friendbuy.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Friendbuy\naid: friendbuy\nurl: https://www.friendbuy.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Friendbuy provides services for businesses to acquire new customers and monetize content\nrestricted_uses:\n- summary: No false information or defamatory content\n  text: Give us any false or misleading information in connection with your use of the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Register for any account if you are under\
  \ 13 years.\n"
source_yaml_url: https://artifacts.apis.io/friendbuy/eligibility/friendbuy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Friendbuy's own page on 2026-11-09.
synthetic: false
tags:
- Referral Marketing
- Loyalty
- Rewards
- E-Commerce
- Marketing
- Advocacy
- Loyalty & Incentives
---
