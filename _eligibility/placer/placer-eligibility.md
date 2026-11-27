---
api_specs:
- filename: placer-account-info-api-openapi.yml
  format: yaml
  label: Placer Account Info API
  slug: placer-account-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-account-info-api-openapi.yml
- filename: placer-loyalty-reports-api-openapi.yml
  format: yaml
  label: Placer Loyalty Reports API
  slug: placer-loyalty-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-loyalty-reports-api-openapi.yml
- filename: placer-manage-pois-api-openapi.yml
  format: yaml
  label: Placer Manage POIs API
  slug: placer-manage-pois-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-manage-pois-api-openapi.yml
- filename: placer-ranking-reports-api-openapi.yml
  format: yaml
  label: Placer Ranking Reports API
  slug: placer-ranking-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-ranking-reports-api-openapi.yml
- filename: placer-retail-sales-reports-api-openapi.yml
  format: yaml
  label: Placer Retail Sales Reports API
  slug: placer-retail-sales-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-retail-sales-reports-api-openapi.yml
- filename: placer-trade-area-reports-api-openapi.yml
  format: yaml
  label: Placer Trade Area Reports API
  slug: placer-trade-area-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-trade-area-reports-api-openapi.yml
- filename: placer-visitor-journey-reports-api-openapi.yml
  format: yaml
  label: Placer Visitor Journey Reports API
  slug: placer-visitor-journey-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-visitor-journey-reports-api-openapi.yml
- filename: placer-visits-reports-api-openapi.yml
  format: yaml
  label: Placer Visits Reports API
  slug: placer-visits-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placer/openapi/placer-visits-reports-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: USE OF THE SERVICES IS VOID WHERE PROHIBITED.
  entity_types:
  - text: If you use the Services on behalf of a company, organization, or other entity, then (a) you represent and warrant that you are an authorized representative of the entity with the authority to bind the entity to the Agreement
    type: business
  minimum_age:
    text: The Services are not designed for use by or in connection with anyone under the age of 18
    value: '18'
  restricted_uses:
  - summary: Employment, health care, credit or insurance eligibility
    text: in connection with establishing eligibility for employment, health care, credit or insurance
  - summary: Law enforcement sales
    text: to market or sell to law enforcement agencies or to any governmental agency to be used for a law enforcement purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use some of the Services, you may be required to create an account with Placer
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Placer
provenance_date: '2026-11-10'
provider_name: Placer
provider_slug: placer
slug: placer-eligibility
source_date: '2026-11-10'
source_filename: placer-eligibility.yml
source_heading: Eligibility
source_page: https://www.placer.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Placer\naid: placer\nurl: https://www.placer.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: USE OF THE SERVICES IS VOID WHERE PROHIBITED.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company, organization, or other entity, then (a) you represent and\n    warrant that you are an authorized representative of the entity with the authority to bind the entity to the\n    Agreement\nrestricted_uses:\n- summary: Employment, health care, credit or insurance eligibility\n  text: in connection with establishing eligibility for employment,\
  \ health care, credit or insurance\n- summary: Law enforcement sales\n  text: to market or sell to law enforcement agencies or to any governmental agency to be used for a law enforcement\n    purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use some of the Services, you may be required to create an account with Placer\nminimum_age:\n  value: '18'\n  text: The Services are not designed for use by or in connection with anyone under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/placer/eligibility/placer-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Placer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Location Analytics
- Foot Traffic
- Geospatial
- Retail Analytics
- Real Estate
- Consumer Insights
- Data
---
