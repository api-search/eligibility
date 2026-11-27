---
api_specs:
- filename: stotles-buyers-api-openapi.yml
  format: yaml
  label: Stotles Buyers API
  slug: stotles-buyers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stotles/openapi/stotles-buyers-api-openapi.yml
- filename: stotles-frameworks-api-openapi.yml
  format: yaml
  label: Stotles Frameworks API
  slug: stotles-frameworks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stotles/openapi/stotles-frameworks-api-openapi.yml
- filename: stotles-notices-api-openapi.yml
  format: yaml
  label: Stotles Notices API
  slug: stotles-notices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stotles/openapi/stotles-notices-api-openapi.yml
- filename: stotles-suppliers-api-openapi.yml
  format: yaml
  label: Stotles Suppliers API
  slug: stotles-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stotles/openapi/stotles-suppliers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: it is entering into this Agreement for business purposes only, i.e. it is not contracting as a 'consumer'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned countries and parties
    text: The Customer shall not export, re-export, transfer or otherwise make available any Data to any Embargoed Country or Restricted Party
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
name: Stotles
provenance_date: '2026-11-10'
provider_name: Stotles
provider_slug: stotles
slug: stotles-eligibility
source_date: '2026-11-10'
source_filename: stotles-eligibility.yml
source_heading: Eligibility
source_page: https://www.stotles.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stotles\naid: stotles\nurl: https://www.stotles.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: it is entering into this Agreement for business purposes only, i.e. it is not contracting as a 'consumer'\nrestricted_uses:\n- summary: Sanctioned countries and parties\n  text: The Customer shall not export, re-export, transfer or otherwise make available any Data to any Embargoed\n    Country or Restricted Party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stotles/eligibility/stotles-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Stotles's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Procurement
- Public Sector
- Government
- Tenders
- Sales Intelligence
- B2G
- Market Intelligence
- OpenAPI
- MCP
- Agent-Native
- Contract Awards
- Framework Agreements
- CPV
- United Kingdom
- Ireland
- GovTech
---
