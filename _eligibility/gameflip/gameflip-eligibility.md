---
api_specs:
- filename: gameflip-account-api-openapi.yml
  format: yaml
  label: Gameflip Account API
  slug: gameflip-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameflip/openapi/gameflip-account-api-openapi.yml
- filename: gameflip-exchange-api-openapi.yml
  format: yaml
  label: Gameflip Exchange API
  slug: gameflip-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameflip/openapi/gameflip-exchange-api-openapi.yml
- filename: gameflip-listing-api-openapi.yml
  format: yaml
  label: Gameflip Listing API
  slug: gameflip-listing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameflip/openapi/gameflip-listing-api-openapi.yml
- filename: gameflip-profile-api-openapi.yml
  format: yaml
  label: Gameflip Profile API
  slug: gameflip-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameflip/openapi/gameflip-profile-api-openapi.yml
- filename: gameflip-steam-bulk-api-openapi.yml
  format: yaml
  label: Gameflip Steam Bulk API
  slug: gameflip-steam-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameflip/openapi/gameflip-steam-bulk-api-openapi.yml
- filename: gameflip-steam-escrow-api-openapi.yml
  format: yaml
  label: Gameflip Steam Escrow API
  slug: gameflip-steam-escrow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gameflip/openapi/gameflip-steam-escrow-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This provision is void where prohibited by law and the right to access the Services is hereby denied in such jurisdictions.
  entity_types:
  - text: individuals who are 18 years and older who can form legally binding contracts under applicable law
    type: individual
  - text: If you are registering as a business entity, you personally guarantee that you have the authority to bind the entity to this Agreement.
    type: business
  minimum_age:
    text: individuals who are 18 years and older who can form legally binding contracts under applicable law, and (b) individuals who are between the ages of 13 and 18 who use the Services through an account owned by a parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: Prohibited items
    text: Involve the sale of any Prohibited Items
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Gameflip may require the account owner to provide additional identification information, including, without limitation, a copy of a valid driver's license (or other form of government issued identification).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gameflip
provenance_date: '2026-11-09'
provider_name: Gameflip
provider_slug: gameflip
slug: gameflip-eligibility
source_date: '2026-11-09'
source_filename: gameflip-eligibility.yml
source_heading: Eligibility
source_page: https://gameflip.com/about/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gameflip\naid: gameflip\nurl: https://gameflip.com/about/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This provision is void where prohibited by law and the right to access the Services is hereby denied in\n    such jurisdictions.\nentity_types:\n- type: individual\n  text: individuals who are 18 years and older who can form legally binding contracts under applicable law\n- type: business\n  text: If you are registering as a business entity, you personally guarantee that you have the authority to bind\n    the entity to this Agreement.\nrestricted_uses:\n- summary: Prohibited\
  \ items\n  text: Involve the sale of any Prohibited Items\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Gameflip may require the account owner to provide additional identification information, including, without\n    limitation, a copy of a valid driver's license (or other form of government issued identification).\nminimum_age:\n  value: '18'\n  text: individuals who are 18 years and older who can form legally binding contracts under applicable law, and\n    (b) individuals who are between the ages of 13 and 18 who use the Services through an account owned by a parent\n    or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/gameflip/eligibility/gameflip-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Gameflip's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Marketplace
- Digital Goods
- E-Commerce
- Payments
- Wallets
- Listings
- Steam
- Gift Cards
---
