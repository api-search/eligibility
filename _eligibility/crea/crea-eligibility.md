---
api_specs:
- filename: crea-destination-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Destination API
  slug: crea-destination-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-destination-api-openapi.yml
- filename: crea-lead-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Lead API
  slug: crea-lead-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-lead-api-openapi.yml
- filename: crea-member-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Member API
  slug: crea-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-member-api-openapi.yml
- filename: crea-office-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Office API
  slug: crea-office-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-office-api-openapi.yml
- filename: crea-openhouse-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Open House API
  slug: crea-openhouse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-openhouse-api-openapi.yml
- filename: crea-property-api-openapi.yml
  format: yaml
  label: CREA (REALTOR.ca) Property API
  slug: crea-property-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crea/openapi/crea-property-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Participating Brokerage – a member brokerage that is actively engaged in providing real estate brokerage services to buyers or sellers in real estate transactions and who consents to display of its listings on Websites through the DDF®.
    type: business
  - text: Participating Salesperson – a REALTOR® that is registered with a Participating Brokerage who also chooses to participate in the DDF® with the consent of his or her brokerage.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No online brokerage websites
    text: Participants shall not use the Listing Content they receive through the DDF® in the operation of a Website through which a member provides online brokerage services to consumers.
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
name: CREA (REALTOR.ca)
provenance_date: '2026-11-09'
provider_name: CREA (REALTOR.ca)
provider_slug: crea
slug: crea-eligibility
source_date: '2026-11-09'
source_filename: crea-eligibility.yml
source_heading: Eligibility
source_page: https://www.crea.ca/files/technology/english/DDFR-Policy-and-Rules-February-2024-ENG.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CREA (REALTOR.ca)\naid: crea\nurl: https://www.crea.ca/files/technology/english/DDFR-Policy-and-Rules-February-2024-ENG.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Participating Brokerage – a member brokerage that is actively engaged in providing real estate brokerage\n    services to buyers or sellers in real estate transactions and who consents to display of its listings on Websites\n    through the DDF®.\n- type: individual\n  text: Participating Salesperson – a REALTOR® that is registered with a Participating Brokerage who\
  \ also chooses\n    to participate in the DDF® with the consent of his or her brokerage.\nrestricted_uses:\n- summary: No online brokerage websites\n  text: Participants shall not use the Listing Content they receive through the DDF® in the operation of a Website\n    through which a member provides online brokerage services to consumers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crea/eligibility/crea-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from CREA (REALTOR.ca)'s own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Canada
- Property Listings
- MLS
- IDX
- RESO
- OData
- Industry Body
- PropTech
- Data Syndication
---
