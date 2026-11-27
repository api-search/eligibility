---
api_specs:
- filename: wallapop-categories-api-openapi.yml
  format: yaml
  label: Wallapop Categories API
  slug: wallapop-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wallapop/openapi/wallapop-categories-api-openapi.yml
- filename: wallapop-delivery-api-openapi.yml
  format: yaml
  label: Wallapop Delivery API
  slug: wallapop-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wallapop/openapi/wallapop-delivery-api-openapi.yml
- filename: wallapop-disputes-api-openapi.yml
  format: yaml
  label: Wallapop Disputes API
  slug: wallapop-disputes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wallapop/openapi/wallapop-disputes-api-openapi.yml
- filename: wallapop-items-api-openapi.yml
  format: yaml
  label: Wallapop Items API
  slug: wallapop-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wallapop/openapi/wallapop-items-api-openapi.yml
- filename: wallapop-transactions-api-openapi.yml
  format: yaml
  label: Wallapop Transactions API
  slug: wallapop-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wallapop/openapi/wallapop-transactions-api-openapi.yml
- filename: wallapop-webhooks-api-openapi.yml
  format: yaml
  label: Wallapop Webhooks API
  slug: wallapop-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wallapop/openapi/wallapop-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - ES
    - IT
    - PT
    text: Wallapop currently operates only in Spain, Italy and Portugal.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content and listings
    text: It is not permitted to post advertisements containing images of a sexual nature.
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
name: Wallapop
provenance_date: '2026-11-10'
provider_name: Wallapop
provider_slug: wallapop
slug: wallapop-eligibility
source_date: '2026-11-10'
source_filename: wallapop-eligibility.yml
source_heading: Eligibility
source_page: https://about.wallapop.com/en/legal-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wallapop\naid: wallapop\nurl: https://about.wallapop.com/en/legal-terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - ES\n  - IT\n  - PT\n  excluded: []\n  text: Wallapop currently operates only in Spain, Italy and Portugal.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content and listings\n  text: It is not permitted to post advertisements containing images of a sexual nature.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wallapop/eligibility/wallapop-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Wallapop's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Marketplace
- E-Commerce
- Secondhand
- Classifieds
- Shipping
- Webhook
---
