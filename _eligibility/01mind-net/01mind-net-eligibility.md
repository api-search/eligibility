---
api_specs:
- filename: 01mind-net-campaigns-api-openapi.yml
  format: yaml
  label: 01Mind Campaigns API
  slug: 01mind-net-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/01mind-net/openapi/01mind-net-campaigns-api-openapi.yml
- filename: 01mind-net-charon-api-openapi.yml
  format: yaml
  label: 01Mind Charon API
  slug: 01mind-net-charon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/01mind-net/openapi/01mind-net-charon-api-openapi.yml
- filename: 01mind-net-document-templates-api-openapi.yml
  format: yaml
  label: 01Mind Document Templates API
  slug: 01mind-net-document-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/01mind-net/openapi/01mind-net-document-templates-api-openapi.yml
- filename: 01mind-net-execute-api-openapi.yml
  format: yaml
  label: 01Mind Execute API
  slug: 01mind-net-execute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/01mind-net/openapi/01mind-net-execute-api-openapi.yml
- filename: 01mind-net-research-api-openapi.yml
  format: yaml
  label: 01Mind Research API
  slug: 01mind-net-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/01mind-net/openapi/01mind-net-research-api-openapi.yml
- filename: 01mind-net-sandbox-api-openapi.yml
  format: yaml
  label: 01Mind Sandbox API
  slug: 01mind-net-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/01mind-net/openapi/01mind-net-sandbox-api-openapi.yml
- filename: 01mind-net-token-topups-api-openapi.yml
  format: yaml
  label: 01Mind Token Topups API
  slug: 01mind-net-token-topups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/01mind-net/openapi/01mind-net-token-topups-api-openapi.yml
- filename: 01mind-net-tool-requests-api-openapi.yml
  format: yaml
  label: 01Mind Tool Requests API
  slug: 01mind-net-tool-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/01mind-net/openapi/01mind-net-tool-requests-api-openapi.yml
- filename: 01mind-net-venue-api-openapi.yml
  format: yaml
  label: 01Mind Venue API
  slug: 01mind-net-venue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/01mind-net/openapi/01mind-net-venue-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: We sell two services to businesses in Australia
  entity_types:
  - text: These terms apply to every sale 01Mind makes, to people, businesses and software agents.
    type: individual
  - text: The buyer is the business named in your request, and the person who requests a service confirms they may act for it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unsolicited email
    text: (b) to send email to anyone who has not agreed to receive it
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: No account, signature or separate contract is needed.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 01Mind
provenance_date: '2026-11-09'
provider_name: 01Mind
provider_slug: 01mind-net
slug: 01mind-net-eligibility
source_date: '2026-11-09'
source_filename: 01mind-net-eligibility.yml
source_heading: Eligibility
source_page: https://01mind.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 01Mind\naid: 01mind-net\nurl: https://01mind.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: We sell two services to businesses in Australia\nentity_types:\n- type: individual\n  text: These terms apply to every sale 01Mind makes, to people, businesses and software agents.\n- type: business\n  text: The buyer is the business named in your request, and the person who requests a service confirms they may\n    act for it.\nrestricted_uses:\n- summary: Unsolicited email\n  text: (b) to send email to anyone who has not agreed to receive it\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: No account, signature or separate contract is needed.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/01mind-net/eligibility/01mind-net-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from 01Mind's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Agentic Commerce
- A2A
- MCP
- x402
- Document Generation
- Email
- Legal Research
- Compliance
- Tool Generation
- Agent-Native
- Australia
---
