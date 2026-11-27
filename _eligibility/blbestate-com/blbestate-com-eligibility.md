---
api_specs:
- filename: blbestate-com-agent-api-openapi.yml
  format: yaml
  label: SalesSwipe Agent API
  slug: blbestate-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blbestate-com/openapi/blbestate-com-agent-api-openapi.yml
- filename: blbestate-com-mcp-api-openapi.yml
  format: yaml
  label: SalesSwipe MCP API
  slug: blbestate-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blbestate-com/openapi/blbestate-com-mcp-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The service is offered for lawful real-estate research and business use in the United States.
  entity_types:
  - text: You must be at least 18 and able to form a contract.
    type: individual
  - text: If you use the service for a company, you represent that you can bind that company.
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a contract.
    value: '18'
  restricted_uses:
  - summary: No FCRA-type eligibility screening
    text: Use the service or its output for tenant, credit, employment, insurance, government-benefit or other eligibility screening governed by the Fair Credit Reporting Act or similar law.
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
name: SalesSwipe
provenance_date: '2026-11-09'
provider_name: SalesSwipe
provider_slug: blbestate-com
slug: blbestate-com-eligibility
source_date: '2026-11-09'
source_filename: blbestate-com-eligibility.yml
source_heading: Eligibility
source_page: https://blbestate.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SalesSwipe\naid: blbestate-com\nurl: https://blbestate.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The service is offered for lawful real-estate research and business use in the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a contract.\n- type: business\n  text: If you use the service for a company, you represent that you can bind that company.\nrestricted_uses:\n- summary: No FCRA-type eligibility screening\n  text: Use the service or its output for tenant, credit, employment, insurance, government-benefit\
  \ or other eligibility\n    screening governed by the Fair Credit Reporting Act or similar law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a contract.\n"
source_yaml_url: https://artifacts.apis.io/blbestate-com/eligibility/blbestate-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SalesSwipe's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Platform
- Property
- Sales
- Software-as-a-Service
---
