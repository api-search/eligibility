---
api_specs:
- filename: redocly-health-api-openapi.yml
  format: yaml
  label: Redocly Health API
  slug: redocly-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-health-api-openapi.yml
- filename: redocly-metadata-api-openapi.yml
  format: yaml
  label: Redocly Metadata API
  slug: redocly-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-metadata-api-openapi.yml
- filename: redocly-remotes-api-openapi.yml
  format: yaml
  label: Redocly Remotes API
  slug: redocly-remotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-remotes-api-openapi.yml
- filename: redocly-search-api-openapi.yml
  format: yaml
  label: Redocly Search API
  slug: redocly-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-search-api-openapi.yml
- filename: redocly-status-api-openapi.yml
  format: yaml
  label: Redocly Status API
  slug: redocly-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-status-api-openapi.yml
- filename: redocly-tasks-api-openapi.yml
  format: yaml
  label: Redocly Tasks API
  slug: redocly-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-tasks-api-openapi.yml
- filename: redocly-webhooks-api-openapi.yml
  format: yaml
  label: Redocly Webhooks API
  slug: redocly-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-webhooks-api-openapi.yml
- filename: redocly-to-dos-api-openapi.yml
  format: yaml
  label: Redocly To Dos API
  slug: redocly-to-dos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/redocly/openapi/redocly-to-dos-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Customer” means you, the person, entity or organization that has requested use of the Product.
    type: individual
  - text: IF YOU ARE REGISTERING TO USE THE PRODUCTS OR OTHERWISE USE ANY PRODUCTS ON BEHALF OF AN ENTITY OR OTHER ORGANIZATION
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive analysis
    text: Customer will not use the Products for purposes of competitive analysis of the Products, the development of a competing software product or service
  - summary: Unlawful use
    text: Customer will not use the Products in violation of any federal, state, or local law, regulation or rule
  - summary: Export restrictions
    text: Customer shall not, directly or indirectly, export, re-export or release the Products to, or make the Products accessible from, any jurisdiction or country to which export, re-export or release is prohibited by law
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
name: Redocly
provenance_date: '2026-11-10'
provider_name: Redocly
provider_slug: redocly
slug: redocly-eligibility
source_date: '2026-11-10'
source_filename: redocly-eligibility.yml
source_heading: Eligibility
source_page: https://redocly.com/subscription-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Redocly\naid: redocly\nurl: https://redocly.com/subscription-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “Customer” means you, the person, entity or organization that has requested use of the Product.\n- type: business\n  text: IF YOU ARE REGISTERING TO USE THE PRODUCTS OR OTHERWISE USE ANY PRODUCTS ON BEHALF OF AN ENTITY OR OTHER\n    ORGANIZATION\nrestricted_uses:\n- summary: Competitive analysis\n  text: Customer will not use the Products for purposes of competitive analysis of the Products, the development\n    of\
  \ a competing software product or service\n- summary: Unlawful use\n  text: Customer will not use the Products in violation of any federal, state, or local law, regulation or rule\n- summary: Export restrictions\n  text: Customer shall not, directly or indirectly, export, re-export or release the Products to, or make the Products\n    accessible from, any jurisdiction or country to which export, re-export or release is prohibited by law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/redocly/eligibility/redocly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Redocly's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- API Catalog
- API Documentation
- Arazzo
- Developer Portal
- Governance
- Linting
- MCP
- Monitoring
- OpenAPI
- A2A
---
