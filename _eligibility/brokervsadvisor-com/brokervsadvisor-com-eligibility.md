---
api_specs:
- filename: brokervsadvisor-com-enquiry-api-openapi.yml
  format: yaml
  label: Broker vs Advisor Enquiry API
  slug: brokervsadvisor-com-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brokervsadvisor-com/openapi/brokervsadvisor-com-enquiry-api-openapi.yml
- filename: brokervsadvisor-com-guide-api-openapi.yml
  format: yaml
  label: Broker vs Advisor Guide API
  slug: brokervsadvisor-com-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brokervsadvisor-com/openapi/brokervsadvisor-com-guide-api-openapi.yml
- filename: brokervsadvisor-com-mcp-api-openapi.yml
  format: yaml
  label: Broker vs Advisor MCP API
  slug: brokervsadvisor-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brokervsadvisor-com/openapi/brokervsadvisor-com-mcp-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No reliance as advice
    text: Nothing on it is legal or tax advice or advice on any transaction
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
name: Broker vs Advisor
provenance_date: '2026-11-09'
provider_name: Broker vs Advisor
provider_slug: brokervsadvisor-com
slug: brokervsadvisor-com-eligibility
source_date: '2026-11-09'
source_filename: brokervsadvisor-com-eligibility.yml
source_heading: Eligibility
source_page: https://brokervsadvisor.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Broker vs Advisor\naid: brokervsadvisor-com\nurl: https://brokervsadvisor.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No reliance as advice\n  text: Nothing on it is legal or tax advice or advice on any transaction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brokervsadvisor-com/eligibility/brokervsadvisor-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Broker vs Advisor's own page on 2026-11-09.
synthetic: false
tags:
- Business
- Finance
- Legal
- Advisory
- M&A
---
