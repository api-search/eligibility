---
api_specs:
- filename: fundz-acquisitions-api-openapi.yml
  format: yaml
  label: Fundz Acquisitions API
  slug: fundz-acquisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-acquisitions-api-openapi.yml
- filename: fundz-agreements-api-openapi.yml
  format: yaml
  label: Fundz Agreements API
  slug: fundz-agreements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-agreements-api-openapi.yml
- filename: fundz-crowdfundings-api-openapi.yml
  format: yaml
  label: Fundz Crowdfundings API
  slug: fundz-crowdfundings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-crowdfundings-api-openapi.yml
- filename: fundz-executives-api-openapi.yml
  format: yaml
  label: Fundz Executives API
  slug: fundz-executives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-executives-api-openapi.yml
- filename: fundz-fundings-api-openapi.yml
  format: yaml
  label: Fundz Fundings API
  slug: fundz-fundings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-fundings-api-openapi.yml
- filename: fundz-products-api-openapi.yml
  format: yaml
  label: Fundz Products API
  slug: fundz-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundz/openapi/fundz-products-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Companies with 500 or more employees may pay for Strategic or Firm by invoice, on a quarterly or annual term.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Phone and email contact data compliance
    text: You are responsible for complying with the Telephone Consumer Protection Act, Do Not Call rules and any state calling or messaging laws when you use phone numbers or other contact data from Fundz.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To qualify, you must confirm a work email address at your company's domain.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fundz
provenance_date: '2026-11-09'
provider_name: Fundz
provider_slug: fundz
slug: fundz-eligibility
source_date: '2026-11-09'
source_filename: fundz-eligibility.yml
source_heading: Eligibility
source_page: https://www.fundz.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fundz\naid: fundz\nurl: https://www.fundz.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Companies with 500 or more employees may pay for Strategic or Firm by invoice, on a quarterly or annual\n    term.\nrestricted_uses:\n- summary: Phone and email contact data compliance\n  text: You are responsible for complying with the Telephone Consumer Protection Act, Do Not Call rules and any\n    state calling or messaging laws when you use phone numbers or other contact data from Fundz.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: To qualify, you must confirm a work email address at your company's domain.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fundz/eligibility/fundz-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Fundz's own page on 2026-11-09.
synthetic: false
tags:
- Business Intelligence
- Funding
- Private Markets
- Mergers and Acquisitions
- SEC Filings
- Signals
- Sales Intelligence
- MCP
- Agents
---
