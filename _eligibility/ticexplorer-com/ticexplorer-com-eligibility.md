---
api_specs:
- filename: ticexplorer-com-admin-api-openapi.yml
  format: yaml
  label: ticexplorer-com Admin API
  slug: ticexplorer-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-admin-api-openapi.yml
- filename: ticexplorer-com-analytics-api-openapi.yml
  format: yaml
  label: ticexplorer-com Analytics API
  slug: ticexplorer-com-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-analytics-api-openapi.yml
- filename: ticexplorer-com-claims-api-openapi.yml
  format: yaml
  label: ticexplorer-com Claims API
  slug: ticexplorer-com-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-claims-api-openapi.yml
- filename: ticexplorer-com-codes-api-openapi.yml
  format: yaml
  label: ticexplorer-com Codes API
  slug: ticexplorer-com-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-codes-api-openapi.yml
- filename: ticexplorer-com-guide-api-openapi.yml
  format: yaml
  label: ticexplorer-com Guide API
  slug: ticexplorer-com-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-guide-api-openapi.yml
- filename: ticexplorer-com-plans-api-openapi.yml
  format: yaml
  label: ticexplorer-com Plans API
  slug: ticexplorer-com-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-plans-api-openapi.yml
- filename: ticexplorer-com-providers-api-openapi.yml
  format: yaml
  label: ticexplorer-com Providers API
  slug: ticexplorer-com-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-providers-api-openapi.yml
- filename: ticexplorer-com-rates-api-openapi.yml
  format: yaml
  label: ticexplorer-com Rates API
  slug: ticexplorer-com-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-rates-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it for an organization, you agree on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No patient PHI in queries
    text: Don’t send protected health information or other personal details about patients in queries.
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
name: ticexplorer-com
provenance_date: '2026-11-10'
provider_name: ticexplorer-com
provider_slug: ticexplorer-com
slug: ticexplorer-com-eligibility
source_date: '2026-11-10'
source_filename: ticexplorer-com-eligibility.yml
source_heading: Eligibility
source_page: https://ticexplorer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ticexplorer-com\naid: ticexplorer-com\nurl: https://ticexplorer.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it for an organization, you agree on its behalf.\nrestricted_uses:\n- summary: No patient PHI in queries\n  text: Don’t send protected health information or other personal details about patients in queries.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ticexplorer-com/eligibility/ticexplorer-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ticexplorer-com's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Finance
- Transparency
- Healthcare
---
