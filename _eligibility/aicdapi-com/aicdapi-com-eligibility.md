---
api_specs:
- filename: aicdapi-com-agenda-hits-api-openapi.yml
  format: yaml
  label: aicdapi-com Agenda hits API
  slug: aicdapi-com-agenda-hits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-agenda-hits-api-openapi.yml
- filename: aicdapi-com-customer-civic-data-api-openapi.yml
  format: yaml
  label: aicdapi-com Customer civic data API
  slug: aicdapi-com-customer-civic-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-customer-civic-data-api-openapi.yml
- filename: aicdapi-com-data-reports-api-openapi.yml
  format: yaml
  label: aicdapi-com Data reports API
  slug: aicdapi-com-data-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-data-reports-api-openapi.yml
- filename: aicdapi-com-mcp-api-openapi.yml
  format: yaml
  label: aicdapi-com MCP API
  slug: aicdapi-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-mcp-api-openapi.yml
- filename: aicdapi-com-public-api-specification-api-openapi.yml
  format: yaml
  label: aicdapi-com Public API specification API
  slug: aicdapi-com-public-api-specification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-public-api-specification-api-openapi.yml
- filename: aicdapi-com-research-coverage-api-openapi.yml
  format: yaml
  label: aicdapi-com Research coverage API
  slug: aicdapi-com-research-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-research-coverage-api-openapi.yml
- filename: aicdapi-com-sources-api-openapi.yml
  format: yaml
  label: aicdapi-com Sources API
  slug: aicdapi-com-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aicdapi-com/openapi/aicdapi-com-sources-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: individual
  - text: You must have authority to bind the organization on whose behalf you use the service.
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Not for HIPAA/FISMA-regulated use
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: Not for GLBA violations
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: aicdapi-com
provenance_date: '2026-11-09'
provider_name: aicdapi-com
provider_slug: aicdapi-com
slug: aicdapi-com-eligibility
source_date: '2026-11-09'
source_filename: aicdapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://aicdapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: aicdapi-com\naid: aicdapi-com\nurl: https://aicdapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\n- type: business\n  text: You must have authority to bind the organization on whose behalf you use the service.\nrestricted_uses:\n- summary: Not for HIPAA/FISMA-regulated use\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability\
  \ Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: Not for GLBA violations\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/aicdapi-com/eligibility/aicdapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from aicdapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Civic Data
- Government
- MCP
---
