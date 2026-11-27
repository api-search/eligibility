---
api_specs:
- filename: placestack-com-account-api-openapi.yml
  format: yaml
  label: placestack-com Account API
  slug: placestack-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-account-api-openapi.yml
- filename: placestack-com-case-api-openapi.yml
  format: yaml
  label: placestack-com Case API
  slug: placestack-com-case-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-case-api-openapi.yml
- filename: placestack-com-event-api-openapi.yml
  format: yaml
  label: placestack-com Event API
  slug: placestack-com-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-event-api-openapi.yml
- filename: placestack-com-jurisdiction-api-openapi.yml
  format: yaml
  label: placestack-com Jurisdiction API
  slug: placestack-com-jurisdiction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-jurisdiction-api-openapi.yml
- filename: placestack-com-list-api-openapi.yml
  format: yaml
  label: placestack-com List API
  slug: placestack-com-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-list-api-openapi.yml
- filename: placestack-com-monitor-api-openapi.yml
  format: yaml
  label: placestack-com Monitor API
  slug: placestack-com-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-monitor-api-openapi.yml
- filename: placestack-com-parcel-api-openapi.yml
  format: yaml
  label: placestack-com Parcel API
  slug: placestack-com-parcel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-parcel-api-openapi.yml
- filename: placestack-com-permit-api-openapi.yml
  format: yaml
  label: placestack-com Permit API
  slug: placestack-com-permit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-permit-api-openapi.yml
- filename: placestack-com-suggestion-api-openapi.yml
  format: yaml
  label: placestack-com Suggestion API
  slug: placestack-com-suggestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-suggestion-api-openapi.yml
- filename: placestack-com-usage-api-openapi.yml
  format: yaml
  label: placestack-com Usage API
  slug: placestack-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-usage-api-openapi.yml
- filename: placestack-com-webhook-api-openapi.yml
  format: yaml
  label: placestack-com Webhook API
  slug: placestack-com-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-webhook-api-openapi.yml
- filename: placestack-com-zoning-api-openapi.yml
  format: yaml
  label: placestack-com Zoning API
  slug: placestack-com-zoning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placestack-com/openapi/placestack-com-zoning-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, or a resident of, a country subject to US embargo, and are not on any US government list of prohibited or restricted parties.
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind it, and “you” includes that organization.
    type: business
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: No eligibility decisions about people
    text: Make decisions about a person’s eligibility for credit, employment, insurance or housing.
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
name: placestack-com
provenance_date: '2026-11-10'
provider_name: placestack-com
provider_slug: placestack-com
slug: placestack-com-eligibility
source_date: '2026-11-10'
source_filename: placestack-com-eligibility.yml
source_heading: Eligibility
source_page: https://placestack.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: placestack-com\naid: placestack-com\nurl: https://placestack.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, or a resident of, a country subject to US embargo, and are not\n    on any US government list of prohibited or restricted parties.\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind it, and\n    “you” includes that organization.\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary:\
  \ No eligibility decisions about people\n  text: Make decisions about a person’s eligibility for credit, employment, insurance or housing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/placestack-com/eligibility/placestack-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from placestack-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Data
- Geospatial
- Property
---
