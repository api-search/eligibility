---
api_specs:
- filename: tomorrowlives-com-account-api-openapi.yml
  format: yaml
  label: tomorrowlives-com Account API
  slug: tomorrowlives-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-account-api-openapi.yml
- filename: tomorrowlives-com-jobs-api-openapi.yml
  format: yaml
  label: tomorrowlives-com Jobs API
  slug: tomorrowlives-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-jobs-api-openapi.yml
- filename: tomorrowlives-com-lab-api-openapi.yml
  format: yaml
  label: tomorrowlives-com Lab API
  slug: tomorrowlives-com-lab-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-lab-api-openapi.yml
- filename: tomorrowlives-com-mcp-api-openapi.yml
  format: yaml
  label: tomorrowlives-com MCP API
  slug: tomorrowlives-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-mcp-api-openapi.yml
- filename: tomorrowlives-com-production-engines-api-openapi.yml
  format: yaml
  label: tomorrowlives-com Production engines API
  slug: tomorrowlives-com-production-engines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-production-engines-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to hold a Tomorrow Lives Studio account.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to hold a Tomorrow Lives Studio account.
    value: '13'
  restricted_uses:
  - summary: No illegal content or content sexually exploiting minors
    text: Generate or distribute illegal content, or anything that sexually exploits or endangers minors
  - summary: No content facilitating serious harm
    text: Create content that facilitates serious harm, including weapons, violence, self-harm, or other dangerous activity
  - summary: No impersonation of real people or organizations
    text: Impersonate real people or organizations without their consent
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
name: tomorrowlives-com
provenance_date: '2026-11-10'
provider_name: tomorrowlives-com
provider_slug: tomorrowlives-com
slug: tomorrowlives-com-eligibility
source_date: '2026-11-10'
source_filename: tomorrowlives-com-eligibility.yml
source_heading: Eligibility
source_page: https://tomorrowlives.com/account/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tomorrowlives-com\naid: tomorrowlives-com\nurl: https://tomorrowlives.com/account/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to hold a Tomorrow Lives Studio account.\nrestricted_uses:\n- summary: No illegal content or content sexually exploiting minors\n  text: Generate or distribute illegal content, or anything that sexually exploits or endangers minors\n- summary: No content facilitating serious harm\n  text: Create content that facilitates serious harm, including weapons, violence, self-harm,\
  \ or other dangerous\n    activity\n- summary: No impersonation of real people or organizations\n  text: Impersonate real people or organizations without their consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to hold a Tomorrow Lives Studio account.\n"
source_yaml_url: https://artifacts.apis.io/tomorrowlives-com/eligibility/tomorrowlives-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from tomorrowlives-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Generative
- Engines
- Creative
---
