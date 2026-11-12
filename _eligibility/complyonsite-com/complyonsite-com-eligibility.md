---
api_specs:
- filename: complyonsite-com-digital-waste-tracking-check-api-openapi.yml
  format: yaml
  label: ComplyOnSite Digital Waste Tracking Check API
  slug: complyonsite-com-digital-waste-tracking-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/complyonsite-com/openapi/complyonsite-com-digital-waste-tracking-check-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Plans are sold to businesses in the UK.
  entity_types:
  - text: Plans are sold to businesses in the UK.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not a safety approval
    text: It does not approve a RAMS or say that work is safe, compliant or may start.
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
name: ComplyOnSite
provenance_date: '2026-11-09'
provider_name: ComplyOnSite
provider_slug: complyonsite-com
slug: complyonsite-com-eligibility
source_date: '2026-11-09'
source_filename: complyonsite-com-eligibility.yml
source_heading: Eligibility
source_page: https://complyonsite.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ComplyOnSite\naid: complyonsite-com\nurl: https://complyonsite.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Plans are sold to businesses in the UK.\nentity_types:\n- type: business\n  text: Plans are sold to businesses in the UK.\nrestricted_uses:\n- summary: Not a safety approval\n  text: It does not approve a RAMS or say that work is safe, compliant or may start.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/complyonsite-com/eligibility/complyonsite-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ComplyOnSite's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Health and Safety
- Environmental Compliance
- Waste Management
- RAMS
- MCP
- Open Data
---
