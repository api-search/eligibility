---
api_specs:
- filename: ploid-account-api-openapi.yml
  format: yaml
  label: Ploid Account API
  slug: ploid-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ploid/openapi/ploid-account-api-openapi.yml
- filename: ploid-discovery-api-openapi.yml
  format: yaml
  label: Ploid Discovery API
  slug: ploid-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ploid/openapi/ploid-discovery-api-openapi.yml
- filename: ploid-enrichment-api-openapi.yml
  format: yaml
  label: Ploid Enrichment API
  slug: ploid-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ploid/openapi/ploid-enrichment-api-openapi.yml
- filename: ploid-harness-api-openapi.yml
  format: yaml
  label: Ploid Harness API
  slug: ploid-harness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ploid/openapi/ploid-harness-api-openapi.yml
- filename: ploid-monitors-api-openapi.yml
  format: yaml
  label: Ploid Monitors API
  slug: ploid-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ploid/openapi/ploid-monitors-api-openapi.yml
- filename: ploid-people-api-openapi.yml
  format: yaml
  label: Ploid People API
  slug: ploid-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ploid/openapi/ploid-people-api-openapi.yml
- filename: ploid-search-api-openapi.yml
  format: yaml
  label: Ploid Search API
  slug: ploid-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ploid/openapi/ploid-search-api-openapi.yml
- filename: ploid-social-api-openapi.yml
  format: yaml
  label: Ploid Social API
  slug: ploid-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ploid/openapi/ploid-social-api-openapi.yml
- filename: ploid-linked-in-api-openapi.yml
  format: yaml
  label: Ploid Linked In API
  slug: ploid-linked-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ploid/openapi/ploid-linked-in-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services on behalf of a company or other legal entity, you represent that you have authority to bind that entity, and "you" includes that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-business or harmful use
    text: The Services are intended for lawful business and professional outreach (for example recruiting and sales) only, not for personal, non-business use, harassment, stalking, spam, or unpermitted surveillance.
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
name: Ploid
provenance_date: '2026-11-10'
provider_name: Ploid
provider_slug: ploid
slug: ploid-eligibility
source_date: '2026-11-10'
source_filename: ploid-eligibility.yml
source_heading: Eligibility
source_page: https://ploid.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ploid\naid: ploid\nurl: https://ploid.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other legal entity, you represent that you have authority\n    to bind that entity, and \"you\" includes that entity.\nrestricted_uses:\n- summary: Non-business or harmful use\n  text: The Services are intended for lawful business and professional outreach (for example recruiting and sales)\n    only, not for personal, non-business use, harassment, stalking, spam, or unpermitted surveillance.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ploid/eligibility/ploid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Ploid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- People Data
- People Search
- Contact Enrichment
- Sales Intelligence
- Recruiting
- LinkedIn
- MCP
- Agents
- Data Enrichment
---
