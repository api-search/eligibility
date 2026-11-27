---
api_specs:
- filename: redfin-csv-export-api-openapi.yml
  format: yaml
  label: Redfin CSV Export API
  slug: redfin-csv-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redfin/openapi/redfin-csv-export-api-openapi.yml
- filename: redfin-market-tracker-api-openapi.yml
  format: yaml
  label: Redfin Market Tracker API
  slug: redfin-market-tracker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redfin/openapi/redfin-market-tracker-api-openapi.yml
- filename: redfin-market-trends-api-openapi.yml
  format: yaml
  label: Redfin Market Trends API
  slug: redfin-market-trends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redfin/openapi/redfin-market-trends-api-openapi.yml
- filename: redfin-neighborhood-api-openapi.yml
  format: yaml
  label: Redfin Neighborhood API
  slug: redfin-neighborhood-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redfin/openapi/redfin-neighborhood-api-openapi.yml
- filename: redfin-property-details-api-openapi.yml
  format: yaml
  label: Redfin Property Details API
  slug: redfin-property-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redfin/openapi/redfin-property-details-api-openapi.yml
- filename: redfin-search-api-openapi.yml
  format: yaml
  label: Redfin Search API
  slug: redfin-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redfin/openapi/redfin-search-api-openapi.yml
- filename: redfin-valuation-api-openapi.yml
  format: yaml
  label: Redfin Valuation API
  slug: redfin-valuation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redfin/openapi/redfin-valuation-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that the Services are appropriate or available for use in any particular country or location.
  entity_types:
  - text: To access and use the Services, you must be at least the age of majority in the state, province, or territory where you live or at least 18 years of age.
    type: individual
  minimum_age:
    text: If you are under the age of 13, you may not use the Services and you should not be visiting the Sites or using the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You may not use the Services in any way that violates any law or regulation, this Agreement, any of the Redfin Companies' policies, or any third party policy, that applies to you.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: NO REDFIN COMPANY HAS ANY OBLIGATION TO VERIFY THE IDENTITY OF THE PERSONS USING ITS SERVICES, NOR DOES ANY REDFIN COMPANY HAVE ANY OBLIGATION TO MONITOR THE USE OF ITS SERVICES.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Redfin
provenance_date: '2026-11-10'
provider_name: Redfin
provider_slug: redfin
slug: redfin-eligibility
source_date: '2026-11-10'
source_filename: redfin-eligibility.yml
source_heading: Eligibility
source_page: https://www.redfin.com/about/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Redfin\naid: redfin\nurl: https://www.redfin.com/about/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that the Services are appropriate or available for use in any particular country\n    or location.\nentity_types:\n- type: individual\n  text: To access and use the Services, you must be at least the age of majority in the state, province, or territory\n    where you live or at least 18 years of age.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You may not use the Services in any way that violates any law\
  \ or regulation, this Agreement, any of the\n    Redfin Companies' policies, or any third party policy, that applies to you.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: NO REDFIN COMPANY HAS ANY OBLIGATION TO VERIFY THE IDENTITY OF THE PERSONS USING ITS SERVICES, NOR DOES\n    ANY REDFIN COMPANY HAVE ANY OBLIGATION TO MONITOR THE USE OF ITS SERVICES.\nminimum_age:\n  value: '18'\n  text: If you are under the age of 13, you may not use the Services and you should not be visiting the Sites or\n    using the Services.\n"
source_yaml_url: https://artifacts.apis.io/redfin/eligibility/redfin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Redfin's own page on 2026-11-10.
synthetic: false
tags:
- CSV Export
- GIS
- Home Values
- Housing Market
- Listings
- Property Data
- Real Estate
---
