---
api_specs:
- filename: shopmy-catalog-api-openapi.yml
  format: yaml
  label: ShopMy Catalog API
  slug: shopmy-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopmy/openapi/shopmy-catalog-api-openapi.yml
- filename: shopmy-collections-api-openapi.yml
  format: yaml
  label: ShopMy Collections API
  slug: shopmy-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopmy/openapi/shopmy-collections-api-openapi.yml
- filename: shopmy-links-api-openapi.yml
  format: yaml
  label: ShopMy Links API
  slug: shopmy-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopmy/openapi/shopmy-links-api-openapi.yml
- filename: shopmy-order-reporting-api-openapi.yml
  format: yaml
  label: ShopMy Order Reporting API
  slug: shopmy-order-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopmy/openapi/shopmy-order-reporting-api-openapi.yml
- filename: shopmy-profile-api-openapi.yml
  format: yaml
  label: ShopMy Profile API
  slug: shopmy-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopmy/openapi/shopmy-profile-api-openapi.yml
- filename: shopmy-oauth-api-openapi.yml
  format: yaml
  label: ShopMy O Auth API
  slug: shopmy-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopmy/openapi/shopmy-oauth-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that content available within the Services is appropriate or available for use in locations outside the United States.
  entity_types:
  - text: If you create or administer an account on behalf of a company, organization, or other legal entity, you represent, warrant, and covenant that (a) you have full legal authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: Children under the age of 13 may not use the Services
    value: '13'
  restricted_uses:
  - summary: Sanctions and export controls
    text: You agree not to use the Services in violation of such laws, including applicable export control and sanctions laws of the United States and other jurisdictions.
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
name: ShopMy
provenance_date: '2026-11-10'
provider_name: ShopMy
provider_slug: shopmy
slug: shopmy-eligibility
source_date: '2026-11-10'
source_filename: shopmy-eligibility.yml
source_heading: Eligibility
source_page: https://shopmy.us/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShopMy\naid: shopmy\nurl: https://shopmy.us/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that content available within the Services is appropriate or available for use\n    in locations outside the United States.\nentity_types:\n- type: business\n  text: If you create or administer an account on behalf of a company, organization, or other legal entity, you\n    represent, warrant, and covenant that (a) you have full legal authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Sanctions and export controls\n \
  \ text: You agree not to use the Services in violation of such laws, including applicable export control and sanctions\n    laws of the United States and other jurisdictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Children under the age of 13 may not use the Services\n"
source_yaml_url: https://artifacts.apis.io/shopmy/eligibility/shopmy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ShopMy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- Creator Economy
- Creator Commerce
- Affiliate Marketing
- Influencer Marketing
- E-Commerce
- Retail
---
