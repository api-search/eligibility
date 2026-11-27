---
api_specs:
- filename: havenly-addresses-api-openapi.yml
  format: yaml
  label: Havenly Addresses API
  slug: havenly-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-addresses-api-openapi.yml
- filename: havenly-attribute-types-api-openapi.yml
  format: yaml
  label: Havenly Attribute Types API
  slug: havenly-attribute-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-attribute-types-api-openapi.yml
- filename: havenly-authentication-api-openapi.yml
  format: yaml
  label: Havenly Authentication API
  slug: havenly-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-authentication-api-openapi.yml
- filename: havenly-board-feedback-api-openapi.yml
  format: yaml
  label: Havenly Board Feedback API
  slug: havenly-board-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-board-feedback-api-openapi.yml
- filename: havenly-board-feedback-questions-api-openapi.yml
  format: yaml
  label: Havenly Board Feedback Questions API
  slug: havenly-board-feedback-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-board-feedback-questions-api-openapi.yml
- filename: havenly-board-products-api-openapi.yml
  format: yaml
  label: Havenly Board Products API
  slug: havenly-board-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-board-products-api-openapi.yml
- filename: havenly-searched-vendor-variants-api-openapi.yml
  format: yaml
  label: Havenly Searched Vendor Variants API
  slug: havenly-searched-vendor-variants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-searched-vendor-variants-api-openapi.yml
- filename: havenly-user-opinions-api-openapi.yml
  format: yaml
  label: Havenly User Opinions API
  slug: havenly-user-opinions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-user-opinions-api-openapi.yml
- filename: havenly-user-profile-api-openapi.yml
  format: yaml
  label: Havenly User Profile API
  slug: havenly-user-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-user-profile-api-openapi.yml
- filename: havenly-users-api-openapi.yml
  format: yaml
  label: Havenly Users API
  slug: havenly-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-users-api-openapi.yml
- filename: havenly-vendor-variants-api-openapi.yml
  format: yaml
  label: Havenly Vendor Variants API
  slug: havenly-vendor-variants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/havenly/openapi/havenly-vendor-variants-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S Government embargo
  entity_types:
  - text: an individual user ("you") or the Subscribing Entity
    type: individual
  - text: If you are using or opening an account on the Service on behalf of a company, entity, or organization (each a "Subscribing Entity")
    type: business
  minimum_age:
    text: No part of the Service is directed to persons under the age of 16.
    value: '16'
  restricted_uses:
  - summary: No commercial solicitation via the Service
    text: You shall not use the Service, without HAVENLY's express written consent, to communicate or facilitate any commercial advertisement or solicitation, except as expressly permitted in the EULA.
  - summary: Use only in manner consistent with individual human usage
    text: or otherwise access or use the Service in a manner inconsistent with individual human usage.
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
name: Havenly
provenance_date: '2026-11-09'
provider_name: Havenly
provider_slug: havenly
slug: havenly-eligibility
source_date: '2026-11-09'
source_filename: havenly-eligibility.yml
source_heading: Eligibility
source_page: https://havenly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Havenly\naid: havenly\nurl: https://havenly.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S Government embargo\nentity_types:\n- type: individual\n  text: an individual user (\"you\") or the Subscribing Entity\n- type: business\n  text: If you are using or opening an account on the Service on behalf of a company, entity, or organization (each\n    a \"Subscribing Entity\")\nrestricted_uses:\n- summary: No commercial solicitation via the Service\n  text: You shall not use the Service, without HAVENLY's express written\
  \ consent, to communicate or facilitate any\n    commercial advertisement or solicitation, except as expressly permitted in the EULA.\n- summary: Use only in manner consistent with individual human usage\n  text: or otherwise access or use the Service in a manner inconsistent with individual human usage.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: No part of the Service is directed to persons under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/havenly/eligibility/havenly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Havenly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Interior Design
- Home Decor
- Furniture
- E-Commerce
- Marketplace
- Design
- Retail
- Artificial Intelligence
---
