---
api_specs:
- filename: propraven-com-account-api-openapi.yml
  format: yaml
  label: propraven-com Account API
  slug: propraven-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-account-api-openapi.yml
- filename: propraven-com-coverage-api-openapi.yml
  format: yaml
  label: propraven-com Coverage API
  slug: propraven-com-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-coverage-api-openapi.yml
- filename: propraven-com-credits-api-openapi.yml
  format: yaml
  label: propraven-com Credits API
  slug: propraven-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-credits-api-openapi.yml
- filename: propraven-com-deals-api-openapi.yml
  format: yaml
  label: propraven-com Deals API
  slug: propraven-com-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-deals-api-openapi.yml
- filename: propraven-com-distribution-api-openapi.yml
  format: yaml
  label: propraven-com Distribution API
  slug: propraven-com-distribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-distribution-api-openapi.yml
- filename: propraven-com-leads-api-openapi.yml
  format: yaml
  label: propraven-com Leads API
  slug: propraven-com-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-leads-api-openapi.yml
- filename: propraven-com-market-api-openapi.yml
  format: yaml
  label: propraven-com Market API
  slug: propraven-com-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-market-api-openapi.yml
- filename: propraven-com-owners-api-openapi.yml
  format: yaml
  label: propraven-com Owners API
  slug: propraven-com-owners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-owners-api-openapi.yml
- filename: propraven-com-parcels-api-openapi.yml
  format: yaml
  label: propraven-com Parcels API
  slug: propraven-com-parcels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-parcels-api-openapi.yml
- filename: propraven-com-property-intelligence-api-openapi.yml
  format: yaml
  label: propraven-com Property Intelligence API
  slug: propraven-com-property-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-property-intelligence-api-openapi.yml
- filename: propraven-com-search-api-openapi.yml
  format: yaml
  label: propraven-com Search API
  slug: propraven-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-search-api-openapi.yml
- filename: propraven-com-storefront-api-openapi.yml
  format: yaml
  label: propraven-com Storefront API
  slug: propraven-com-storefront-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-storefront-api-openapi.yml
- filename: propraven-com-verify-api-openapi.yml
  format: yaml
  label: propraven-com Verify API
  slug: propraven-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-verify-api-openapi.yml
- filename: propraven-com-watch-api-openapi.yml
  format: yaml
  label: propraven-com Watch API
  slug: propraven-com-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-watch-api-openapi.yml
- filename: propraven-com-webhooks-api-openapi.yml
  format: yaml
  label: propraven-com Webhooks API
  slug: propraven-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-webhooks-api-openapi.yml
- filename: propraven-com-zoning-api-openapi.yml
  format: yaml
  label: propraven-com Zoning API
  slug: propraven-com-zoning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/propraven-com/openapi/propraven-com-zoning-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: No GLBA-violating use
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  - summary: No consumer reporting use
    text: PropRaven is not a consumer reporting agency and does not provide consumer reports under the Fair Credit Reporting Act
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
name: propraven-com
provenance_date: '2026-11-10'
provider_name: propraven-com
provider_slug: propraven-com
slug: propraven-com-eligibility
source_date: '2026-11-10'
source_filename: propraven-com-eligibility.yml
source_heading: Eligibility
source_page: https://propraven.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: propraven-com\naid: propraven-com\nurl: https://propraven.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: No GLBA-violating use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\n- summary: No consumer reporting use\n  text: PropRaven\
  \ is not a consumer reporting agency and does not provide consumer reports under the Fair Credit\n    Reporting Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/propraven-com/eligibility/propraven-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from propraven-com's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- Data
- Property Intelligence
- US
---
