---
api_specs:
- filename: orderful-conversion-api-openapi.yml
  format: yaml
  label: Orderful Conversion API
  slug: orderful-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-conversion-api-openapi.yml
- filename: orderful-delivery-api-openapi.yml
  format: yaml
  label: Orderful Delivery API
  slug: orderful-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-delivery-api-openapi.yml
- filename: orderful-inbox-api-openapi.yml
  format: yaml
  label: Orderful Inbox API
  slug: orderful-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-inbox-api-openapi.yml
- filename: orderful-label-api-openapi.yml
  format: yaml
  label: Orderful Label API
  slug: orderful-label-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-label-api-openapi.yml
- filename: orderful-organization-api-openapi.yml
  format: yaml
  label: Orderful Organization API
  slug: orderful-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-organization-api-openapi.yml
- filename: orderful-poller-api-openapi.yml
  format: yaml
  label: Orderful Poller API
  slug: orderful-poller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-poller-api-openapi.yml
- filename: orderful-relationship-api-openapi.yml
  format: yaml
  label: Orderful Relationship API
  slug: orderful-relationship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-relationship-api-openapi.yml
- filename: orderful-transaction-api-openapi.yml
  format: yaml
  label: Orderful Transaction API
  slug: orderful-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-transaction-api-openapi.yml
- filename: orderful-transaction-v3-api-openapi.yml
  format: yaml
  label: Orderful Transaction (v3) API
  slug: orderful-transaction-v3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/orderful/openapi/orderful-transaction-v3-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: if you are located in a country that is subject to embargo under the laws of the United States (or under similar laws applicable to you) you may not engage in commercial activities using the Services unless authorized by applicable laws.
  entity_types:
  - text: If you are registering or using the Services on behalf of your company, you represent and certify that you are an authorized representative of your company with the right to bind your company to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Embargoed or sanctioned parties
    text: If you are on the U.S. Treasury Department’s list of Specially Designated Nationals (or an equivalent lists), you may not engage in commercial or business activities using the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to create an account to become a registered user and/or provide us with information about yourself in order to use or access certain features of this Site or the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Orderful
provenance_date: '2026-11-10'
provider_name: Orderful
provider_slug: orderful
slug: orderful-eligibility
source_date: '2026-11-10'
source_filename: orderful-eligibility.yml
source_heading: Eligibility
source_page: https://www.orderful.com/terms/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Orderful\naid: orderful\nurl: https://www.orderful.com/terms/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: if you are located in a country that is subject to embargo under the laws of the United States (or under\n    similar laws applicable to you) you may not engage in commercial activities using the Services unless authorized\n    by applicable laws.\nentity_types:\n- type: business\n  text: If you are registering or using the Services on behalf of your company, you represent and certify that you\n    are an authorized representative of your company with the right\
  \ to bind your company to these Terms\nrestricted_uses:\n- summary: Embargoed or sanctioned parties\n  text: If you are on the U.S. Treasury Department’s list of Specially Designated Nationals (or an equivalent lists),\n    you may not engage in commercial or business activities using the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to create an account to become a registered user and/or provide us with information\n    about yourself in order to use or access certain features of this Site or the Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/orderful/eligibility/orderful-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Orderful's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EDI
- Electronic Data Interchange
- Supply Chain
- B2B
- Logistics
- Retail
- Transaction
- Integration
---
