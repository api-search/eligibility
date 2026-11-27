---
api_specs:
- filename: starbucks-loyalty-api-openapi.yml
  format: yaml
  label: Starbucks Loyalty API
  slug: starbucks-loyalty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbucks/openapi/starbucks-loyalty-api-openapi.yml
- filename: starbucks-menu-api-openapi.yml
  format: yaml
  label: Starbucks Menu API
  slug: starbucks-menu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbucks/openapi/starbucks-menu-api-openapi.yml
- filename: starbucks-orders-api-openapi.yml
  format: yaml
  label: Starbucks Orders API
  slug: starbucks-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbucks/openapi/starbucks-orders-api-openapi.yml
- filename: starbucks-status-api-openapi.yml
  format: yaml
  label: Starbucks Status API
  slug: starbucks-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbucks/openapi/starbucks-status-api-openapi.yml
- filename: starbucks-stores-api-openapi.yml
  format: yaml
  label: Starbucks Stores API
  slug: starbucks-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbucks/openapi/starbucks-stores-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: he/she is not located in a country that is subject to a U.S. government embargo, or that has been designated by the U.S. government as a “terrorist supporting” country
  entity_types:
  - text: A USER MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE SITES.
    type: individual
  minimum_age:
    text: A USER MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE SITES.
    value: '13'
  restricted_uses:
  - summary: Prohibited uses of the Sites
    text: In no event may the Sites be used in a manner that (a) harasses, abuses, stalks, threatens, defames, or otherwise infringes or violates the rights of any other party
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to participate in certain areas or use certain functions of our Sites, you may need to register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Starbucks
provenance_date: '2026-11-10'
provider_name: Starbucks
provider_slug: starbucks
slug: starbucks-eligibility
source_date: '2026-11-10'
source_filename: starbucks-eligibility.yml
source_heading: Eligibility
source_page: https://www.starbucks.com/terms/starbucks-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Starbucks\naid: starbucks\nurl: https://www.starbucks.com/terms/starbucks-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: he/she is not located in a country that is subject to a U.S. government embargo, or that has been designated\n    by the U.S. government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: A USER MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE SITES.\nrestricted_uses:\n- summary: Prohibited uses of the Sites\n  text: In no event may the Sites be used in a manner that (a) harasses, abuses, stalks, threatens, defames, or\n\
  \    otherwise infringes or violates the rights of any other party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to participate in certain areas or use certain functions of our Sites, you may need to register\n    for an account.\nminimum_age:\n  value: '13'\n  text: A USER MUST BE AT LEAST AGE 13 TO ACCESS AND USE THE SITES.\n"
source_yaml_url: https://artifacts.apis.io/starbucks/eligibility/starbucks-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Starbucks's own page on 2026-11-10.
synthetic: false
tags:
- Coffee
- Food Service
- Loyalty
- Ordering
- Retail
- Fortune 500
- Restaurant
- Food and Beverage
---
