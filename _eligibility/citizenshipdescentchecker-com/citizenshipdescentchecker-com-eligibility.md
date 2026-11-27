---
api_specs:
- filename: citizenshipdescentchecker-com-enquiry-api-openapi.yml
  format: yaml
  label: Citizenship Descent Checker Enquiry API
  slug: citizenshipdescentchecker-com-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citizenshipdescentchecker-com/openapi/citizenshipdescentchecker-com-enquiry-api-openapi.yml
- filename: citizenshipdescentchecker-com-guide-api-openapi.yml
  format: yaml
  label: Citizenship Descent Checker Guide API
  slug: citizenshipdescentchecker-com-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citizenshipdescentchecker-com/openapi/citizenshipdescentchecker-com-guide-api-openapi.yml
- filename: citizenshipdescentchecker-com-mcp-api-openapi.yml
  format: yaml
  label: Citizenship Descent Checker MCP API
  slug: citizenshipdescentchecker-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citizenshipdescentchecker-com/openapi/citizenshipdescentchecker-com-mcp-api-openapi.yml
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
  - summary: Not legal or immigration advice
    text: nothing here is legal or immigration advice
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
name: Citizenship Descent Checker
provenance_date: '2026-11-09'
provider_name: Citizenship Descent Checker
provider_slug: citizenshipdescentchecker-com
slug: citizenshipdescentchecker-com-eligibility
source_date: '2026-11-09'
source_filename: citizenshipdescentchecker-com-eligibility.yml
source_heading: Eligibility
source_page: https://citizenshipdescentchecker.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Citizenship Descent Checker\naid: citizenshipdescentchecker-com\nurl: https://citizenshipdescentchecker.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not legal or immigration advice\n  text: nothing here is legal or immigration advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/citizenshipdescentchecker-com/eligibility/citizenshipdescentchecker-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Citizenship Descent Checker's own page on 2026-11-09.
synthetic: false
tags:
- Citizenship
- Descent
- Canada
- Immigration
- Guides
---
