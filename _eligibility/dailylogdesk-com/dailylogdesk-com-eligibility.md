---
api_specs:
- filename: dailylogdesk-com-dataset-api-openapi.yml
  format: yaml
  label: DailyLogDesk Dataset API
  slug: dailylogdesk-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailylogdesk-com/openapi/dailylogdesk-com-dataset-api-openapi.yml
- filename: dailylogdesk-com-mcp-api-openapi.yml
  format: yaml
  label: DailyLogDesk MCP API
  slug: dailylogdesk-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailylogdesk-com/openapi/dailylogdesk-com-mcp-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Purchase is offered to people acting for purposes related to their trade or profession.
    type: business
  minimum_age:
    text: null
    value: null
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
name: DailyLogDesk
provenance_date: '2026-11-09'
provider_name: DailyLogDesk
provider_slug: dailylogdesk-com
slug: dailylogdesk-com-eligibility
source_date: '2026-11-09'
source_filename: dailylogdesk-com-eligibility.yml
source_heading: Eligibility
source_page: https://dailylogdesk.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DailyLogDesk\naid: dailylogdesk-com\nurl: https://dailylogdesk.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Purchase is offered to people acting for purposes related to their trade or profession.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dailylogdesk-com/eligibility/dailylogdesk-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from DailyLogDesk's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Site Records
- Incident Reporting
- Risk Assessment
- Health and Safety
- Contractors
- Quotes
---
