---
api_specs:
- filename: tinyfish-automation-api-openapi.yml
  format: yaml
  label: TinyFish Automation API
  slug: tinyfish-automation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyfish/openapi/tinyfish-automation-api-openapi.yml
- filename: tinyfish-runs-api-openapi.yml
  format: yaml
  label: TinyFish Runs API
  slug: tinyfish-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyfish/openapi/tinyfish-runs-api-openapi.yml
- filename: tinyfish-tinyfish-browser-api-api-openapi.yml
  format: yaml
  label: TinyFish Browser API
  slug: tinyfish-tinyfish-browser-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyfish/openapi/tinyfish-tinyfish-browser-api-api-openapi.yml
- filename: tinyfish-tinyfish-search-api-api-openapi.yml
  format: yaml
  label: TinyFish Search API
  slug: tinyfish-tinyfish-search-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyfish/openapi/tinyfish-tinyfish-search-api-api-openapi.yml
- filename: tinyfish-usage-api-openapi.yml
  format: yaml
  label: TinyFish Usage API
  slug: tinyfish-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyfish/openapi/tinyfish-usage-api-openapi.yml
- filename: tinyfish-vault-api-openapi.yml
  format: yaml
  label: TinyFish Vault API
  slug: tinyfish-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyfish/openapi/tinyfish-vault-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export Compliance: You represent that you are not located in, or ordinarily resident in, any country or region subject to comprehensive U.S. sanctions'
  entity_types:
  - text: You must be at least 18 years of age to use the Services.
    type: individual
  - text: If you access or use the Services on behalf of an entity (for example, your employer or another organization, the "Client"), you represent and warrant that you have authority to bind the Client to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Services.
    value: '18'
  restricted_uses:
  - summary: Export control and sanctions
    text: You will not access, use, or export the Services in violation of applicable export control or sanctions laws.
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
name: TinyFish
provenance_date: '2026-11-10'
provider_name: TinyFish
provider_slug: tinyfish
slug: tinyfish-eligibility
source_date: '2026-11-10'
source_filename: tinyfish-eligibility.yml
source_heading: Eligibility
source_page: https://www.tinyfish.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TinyFish\naid: tinyfish\nurl: https://www.tinyfish.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export Compliance: You represent that you are not located in, or ordinarily resident in, any country or\n    region subject to comprehensive U.S. sanctions'\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services.\n- type: business\n  text: If you access or use the Services on behalf of an entity (for example, your employer or another organization,\n    the \"Client\"), you represent and warrant that you have authority to bind the\
  \ Client to these Terms.\nrestricted_uses:\n- summary: Export control and sanctions\n  text: You will not access, use, or export the Services in violation of applicable export control or sanctions\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/tinyfish/eligibility/tinyfish-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from TinyFish's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Browser Automation
- Web Scraping
- Search
- MCP
- Data Extraction
---
