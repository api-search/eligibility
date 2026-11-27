---
api_specs:
- filename: liquidonate-donate-api-openapi.yml
  format: yaml
  label: LiquiDonate Donate API
  slug: liquidonate-donate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liquidonate/openapi/liquidonate-donate-api-openapi.yml
- filename: liquidonate-match-api-openapi.yml
  format: yaml
  label: LiquiDonate Match API
  slug: liquidonate-match-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liquidonate/openapi/liquidonate-match-api-openapi.yml
- filename: liquidonate-orders-api-openapi.yml
  format: yaml
  label: LiquiDonate Orders API
  slug: liquidonate-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liquidonate/openapi/liquidonate-orders-api-openapi.yml
- filename: liquidonate-retailer-api-openapi.yml
  format: yaml
  label: LiquiDonate Retailer API
  slug: liquidonate-retailer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liquidonate/openapi/liquidonate-retailer-api-openapi.yml
- filename: liquidonate-ship-api-openapi.yml
  format: yaml
  label: LiquiDonate Ship API
  slug: liquidonate-ship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liquidonate/openapi/liquidonate-ship-api-openapi.yml
- filename: liquidonate-returnsdirect-by-liquidonate-beta-api-openapi.yml
  format: yaml
  label: LiquiDonate ReturnsDirect By LiquiDonate (Beta) API
  slug: liquidonate-returnsdirect-by-liquidonate-beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liquidonate/openapi/liquidonate-returnsdirect-by-liquidonate-beta-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Marketplace is hosted by servers located in the United States. Using the Marketplace may be prohibited or restricted in certain other countries.
  entity_types:
  - text: those individuals, retailers, or other entities that utilize the Marketplace to post information regarding Reclaimable Products
    type: individual
  - text: if you are a retailer, certain enhanced access and features
    type: business
  - text: those nonprofit organizations, schools, or other organizations and individuals that access or otherwise use the Marketplace
    type: nonprofit
  minimum_age:
    text: AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE YOU RESIDE)
    value: '18'
  restricted_uses:
  - summary: Prohibited Items
    text: LiquiDonate prohibits certain items from being posted to or otherwise offered for donation on or through the Marketplace.
  - summary: Donor-imposed restrictions
    text: Some donated items may be under an additional agreement dependent on the donor.
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
name: LiquiDonate
provenance_date: '2026-11-09'
provider_name: LiquiDonate
provider_slug: liquidonate
slug: liquidonate-eligibility
source_date: '2026-11-09'
source_filename: liquidonate-eligibility.yml
source_heading: Eligibility
source_page: https://www.liquidonate.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LiquiDonate\naid: liquidonate\nurl: https://www.liquidonate.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Marketplace is hosted by servers located in the United States. Using the Marketplace may be prohibited\n    or restricted in certain other countries.\nentity_types:\n- type: individual\n  text: those individuals, retailers, or other entities that utilize the Marketplace to post information regarding\n    Reclaimable Products\n- type: business\n  text: if you are a retailer, certain enhanced access and features\n- type: nonprofit\n  text: those nonprofit\
  \ organizations, schools, or other organizations and individuals that access or otherwise\n    use the Marketplace\nrestricted_uses:\n- summary: Prohibited Items\n  text: LiquiDonate prohibits certain items from being posted to or otherwise offered for donation on or through\n    the Marketplace.\n- summary: Donor-imposed restrictions\n  text: Some donated items may be under an additional agreement dependent on the donor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: AT LEAST 18 YEARS OF AGE (OR HAVE REACHED THE AGE OF MAJORITY IN THE JURISDICTION WHERE YOU RESIDE)\n"
source_yaml_url: https://artifacts.apis.io/liquidonate/eligibility/liquidonate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from LiquiDonate's own page on 2026-11-09.
synthetic: false
tags:
- Reverse Logistics
- Returns Management
- Donations
- Non-Profit
- Retail
- E-Commerce
- Sustainability
- Circular Economy
- Shipping
- Supply Chain
- Excess Inventory
- Company
---
