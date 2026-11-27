---
api_specs:
- filename: memberpress-authentication-api-openapi.yml
  format: yaml
  label: MemberPress Authentication API
  slug: memberpress-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-authentication-api-openapi.yml
- filename: memberpress-coupons-api-openapi.yml
  format: yaml
  label: MemberPress Coupons API
  slug: memberpress-coupons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-coupons-api-openapi.yml
- filename: memberpress-events-api-openapi.yml
  format: yaml
  label: MemberPress Events API
  slug: memberpress-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-events-api-openapi.yml
- filename: memberpress-groups-api-openapi.yml
  format: yaml
  label: MemberPress Groups API
  slug: memberpress-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-groups-api-openapi.yml
- filename: memberpress-members-api-openapi.yml
  format: yaml
  label: MemberPress Members API
  slug: memberpress-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-members-api-openapi.yml
- filename: memberpress-memberships-api-openapi.yml
  format: yaml
  label: MemberPress Memberships API
  slug: memberpress-memberships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-memberships-api-openapi.yml
- filename: memberpress-reminders-api-openapi.yml
  format: yaml
  label: MemberPress Reminders API
  slug: memberpress-reminders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-reminders-api-openapi.yml
- filename: memberpress-rules-api-openapi.yml
  format: yaml
  label: MemberPress Rules API
  slug: memberpress-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-rules-api-openapi.yml
- filename: memberpress-subscriptions-api-openapi.yml
  format: yaml
  label: MemberPress Subscriptions API
  slug: memberpress-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-subscriptions-api-openapi.yml
- filename: memberpress-transactions-api-openapi.yml
  format: yaml
  label: MemberPress Transactions API
  slug: memberpress-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-transactions-api-openapi.yml
- filename: memberpress-webhooks-api-openapi.yml
  format: yaml
  label: MemberPress Webhooks API
  slug: memberpress-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/memberpress/openapi/memberpress-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: MemberPress reserves the right to deny access to anyone, including, but not limited to those users who use proxy servers and/or IP addresses residing in certain geographical areas outside of Canada and the United States.
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these terms and conditions
    type: business
  minimum_age:
    text: in order to enter into this Agreement, you must be 18 years old or have otherwise reached the legal age of majority in your jurisdiction of residence or possess legal parental or guardian consent
    value: '18'
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
name: MemberPress
provenance_date: '2026-11-10'
provider_name: MemberPress
provider_slug: memberpress
slug: memberpress-eligibility
source_date: '2026-11-10'
source_filename: memberpress-eligibility.yml
source_heading: Eligibility
source_page: https://memberpress.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MemberPress\naid: memberpress\nurl: https://memberpress.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: MemberPress reserves the right to deny access to anyone, including, but not limited to those users who use\n    proxy servers and/or IP addresses residing in certain geographical areas outside of Canada and the United States.\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity to these terms and conditions\nrestricted_uses: []\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: in order to enter into this Agreement, you must be 18 years old or have otherwise reached the legal age\n    of majority in your jurisdiction of residence or possess legal parental or guardian consent\n"
source_yaml_url: https://artifacts.apis.io/memberpress/eligibility/memberpress-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from MemberPress's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Membership
- Subscription
- WordPress
- Payments
- E-Commerce
- Courses
- Content Management
- Webhook
- MCP
---
