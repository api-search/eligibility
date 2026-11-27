---
api_specs:
- filename: authorizenet-transactions-api-openapi.yml
  format: yaml
  label: Authorize.net Transactions API
  slug: authorizenet-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/authorizenet/openapi/authorizenet-transactions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Site or Services on behalf of your employer, you represent that you are authorized to accept these Terms on your employer's behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized access to secure areas
    text: Access to and use of password protected and/or secure areas of the Site is restricted to authorized users only.
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
name: Authorize.net
provenance_date: '2026-11-09'
provider_name: Authorize.net
provider_slug: authorizenet
slug: authorizenet-eligibility
source_date: '2026-11-09'
source_filename: authorizenet-eligibility.yml
source_heading: Eligibility
source_page: https://www.authorize.net/about-us/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Authorize.net\naid: authorizenet\nurl: https://www.authorize.net/about-us/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Site or Services on behalf of your employer, you represent that you are authorized\n    to accept these Terms on your employer's behalf.\nrestricted_uses:\n- summary: Unauthorized access to secure areas\n  text: Access to and use of password protected and/or secure areas of the Site is restricted to authorized users\n    only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/authorizenet/eligibility/authorizenet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Authorize.net's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Payment Gateway
- Credit Cards
- E-Commerce
- Recurring Billing
- Fraud Prevention
- Webhook
- Financial Services
---
