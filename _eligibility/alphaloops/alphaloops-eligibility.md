---
api_specs:
- filename: alphaloops-carriers-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Carriers API
  slug: alphaloops-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-carriers-api-openapi.yml
- filename: alphaloops-contacts-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Contacts API
  slug: alphaloops-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-contacts-api-openapi.yml
- filename: alphaloops-inspections-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Inspections API
  slug: alphaloops-inspections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-inspections-api-openapi.yml
- filename: alphaloops-vins-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Vins API
  slug: alphaloops-vins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-vins-api-openapi.yml
- filename: alphaloops-custom-data-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Custom Data API
  slug: alphaloops-custom-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-custom-data-api-openapi.yml
- filename: alphaloops-mc-sale-listings-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Mc Sale Listings API
  slug: alphaloops-mc-sale-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-mc-sale-listings-api-openapi.yml
- filename: alphaloops-mc-sales-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Mc Sales API
  slug: alphaloops-mc-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-mc-sales-api-openapi.yml
- filename: alphaloops-peer-groups-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Peer Groups API
  slug: alphaloops-peer-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-peer-groups-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Industry-regulated data interactions
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: GLBA
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: AlphaLoops FMCSA Carrier Data API
provenance_date: '2026-11-09'
provider_name: AlphaLoops FMCSA Carrier Data API
provider_slug: alphaloops
slug: alphaloops-eligibility
source_date: '2026-11-09'
source_filename: alphaloops-eligibility.yml
source_heading: Eligibility
source_page: https://runalphaloops.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AlphaLoops FMCSA Carrier Data API\naid: alphaloops\nurl: https://runalphaloops.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types: []\nrestricted_uses:\n- summary: Industry-regulated data interactions\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act\
  \ (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: GLBA\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/alphaloops/eligibility/alphaloops-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AlphaLoops FMCSA Carrier Data API's own page on 2026-11-09.
synthetic: false
tags:
- fmcsa api
- safer web api
- dot lookup
- carrier data
- Freight
- Trucking
- Motor Carrier
- fleet intelligence
- Sales Intelligence
- MCP Server
- Contact Enrichment
- Risk Management
- Fraud Prevention
---
