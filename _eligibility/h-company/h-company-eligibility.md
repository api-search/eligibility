---
api_specs:
- filename: h-company-agents-api-openapi.yml
  format: yaml
  label: H Company Agents API
  slug: h-company-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-agents-api-openapi.yml
- filename: h-company-browser-profiles-api-openapi.yml
  format: yaml
  label: H Company Browser Profiles API
  slug: h-company-browser-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-browser-profiles-api-openapi.yml
- filename: h-company-environments-api-openapi.yml
  format: yaml
  label: H Company Environments API
  slug: h-company-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-environments-api-openapi.yml
- filename: h-company-quota-api-openapi.yml
  format: yaml
  label: H Company Quota API
  slug: h-company-quota-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-quota-api-openapi.yml
- filename: h-company-schedules-api-openapi.yml
  format: yaml
  label: H Company Schedules API
  slug: h-company-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-schedules-api-openapi.yml
- filename: h-company-sessions-api-openapi.yml
  format: yaml
  label: H Company Sessions API
  slug: h-company-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-sessions-api-openapi.yml
- filename: h-company-skills-api-openapi.yml
  format: yaml
  label: H Company Skills API
  slug: h-company-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-skills-api-openapi.yml
- filename: h-company-vaults-api-openapi.yml
  format: yaml
  label: H Company Vaults API
  slug: h-company-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-vaults-api-openapi.yml
- filename: h-company-webhooks-api-openapi.yml
  format: yaml
  label: H Company Webhooks API
  slug: h-company-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service cannot be used in or for the benefit of, or exported or re-exported to (a) any country or territory subject to a European or U.S. embargo
  entity_types:
  - text: natural persons qualifying as Consumers within the European Union have a legal right of withdrawal for 14 days from the date of purchase.
    type: individual
  - text: For all Users acting in a professional capacity (including legal entities and individual professionals)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Decisions affecting individuals
    text: The User must not use Output concerning an individual for purposes that may have a legal or material impact on that individual
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'Access to the Service requires mandatory creation of a User Account via: A valid email address associated with a display name; or Single sign-on authentication via Google account'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: H Company
provenance_date: '2026-11-09'
provider_name: H Company
provider_slug: h-company
slug: h-company-eligibility
source_date: '2026-11-09'
source_filename: h-company-eligibility.yml
source_heading: Eligibility
source_page: https://hcompany.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: H Company\naid: h-company\nurl: https://hcompany.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service cannot be used in or for the benefit of, or exported or re-exported to (a) any country or territory\n    subject to a European or U.S. embargo\nentity_types:\n- type: individual\n  text: natural persons qualifying as Consumers within the European Union have a legal right of withdrawal for 14\n    days from the date of purchase.\n- type: business\n  text: For all Users acting in a professional capacity (including legal entities and individual professionals)\n\
  restricted_uses:\n- summary: Decisions affecting individuals\n  text: The User must not use Output concerning an individual for purposes that may have a legal or material impact\n    on that individual\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'Access to the Service requires mandatory creation of a User Account via: A valid email address associated\n    with a display name; or Single sign-on authentication via Google account'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/h-company/eligibility/h-company-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from H Company's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Computer Use
- Automation
- Machine Learning
- Browser Automation
- LLM
- MCP
- Developer Tools
- Foundation Models
---
