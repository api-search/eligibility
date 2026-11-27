---
api_specs:
- filename: digiparser-document-processing-api-openapi.yml
  format: yaml
  label: DigiParser Document processing API
  slug: digiparser-document-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digiparser/openapi/digiparser-document-processing-api-openapi.yml
- filename: digiparser-mcp-api-openapi.yml
  format: yaml
  label: DigiParser MCP API
  slug: digiparser-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digiparser/openapi/digiparser-mcp-api-openapi.yml
- filename: digiparser-parsers-api-openapi.yml
  format: yaml
  label: DigiParser Parsers API
  slug: digiparser-parsers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/digiparser/openapi/digiparser-parsers-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo
  minimum_age:
    text: 'You represent that you are over the age of 18. DigiParser (Legal name: Patidar Consultancy) does not permit those under 18 to use the Service.'
    value: '18'
  restricted_uses:
  - summary: Sensitive personal information without authorization
    text: To use the Service to process documents containing sensitive personal information without proper authorization
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
name: DigiParser
provenance_date: '2026-11-09'
provider_name: DigiParser
provider_slug: digiparser
slug: digiparser-eligibility
source_date: '2026-11-09'
source_filename: digiparser-eligibility.yml
source_heading: Eligibility
source_page: https://www.digiparser.com/docs/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DigiParser\naid: digiparser\nurl: https://www.digiparser.com/docs/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo\nentity_types: []\nrestricted_uses:\n- summary: Sensitive personal information without authorization\n  text: To use the Service to process documents containing sensitive personal information without proper authorization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n \
  \ value: '18'\n  text: 'You represent that you are over the age of 18. DigiParser (Legal name: Patidar Consultancy) does not permit\n    those under 18 to use the Service.'\n"
source_yaml_url: https://artifacts.apis.io/digiparser/eligibility/digiparser-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from DigiParser's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Document Processing
- Automation
- Data Extraction
- Artificial Intelligence
---
