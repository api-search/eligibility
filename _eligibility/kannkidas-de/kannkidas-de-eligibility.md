---
api_specs:
- filename: kannkidas-de-agent-api-openapi.yml
  format: yaml
  label: Kann KI das? Sponsoring Agent Agent API
  slug: kannkidas-de-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kannkidas-de/openapi/kannkidas-de-agent-api-openapi.yml
- filename: kannkidas-de-kann-ki-das-api-api-openapi.yml
  format: yaml
  label: Kann KI das? Sponsoring Agent Kann KI Das? API
  slug: kannkidas-de-kann-ki-das-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kannkidas-de/openapi/kannkidas-de-kann-ki-das-api-api-openapi.yml
- filename: kannkidas-de-oauth-api-openapi.yml
  format: yaml
  label: Kann KI das? Sponsoring Agent OAuth API
  slug: kannkidas-de-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kannkidas-de/openapi/kannkidas-de-oauth-api-openapi.yml
- filename: kannkidas-de-search-api-openapi.yml
  format: yaml
  label: Kann KI das? Sponsoring Agent Search API
  slug: kannkidas-de-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kannkidas-de/openapi/kannkidas-de-search-api-openapi.yml
- filename: kannkidas-de-slots-api-openapi.yml
  format: yaml
  label: Kann KI das? Sponsoring Agent Slots API
  slug: kannkidas-de-slots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kannkidas-de/openapi/kannkidas-de-slots-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Sponsorplätze richten sich ausschließlich an Unternehmer im Sinne des § 14 BGB
    type: business
  - text: juristische Personen des öffentlichen Rechts und öffentlich-rechtliche Sondervermögen
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited ad content
    text: Unzulässig sind insbesondere irreführende, rechtswidrige, diskriminierende oder schadsoftwarehaltige Inhalte sowie Angebote für unerlaubte Finanzprodukte, Glücksspiel, Waffen oder pornografische Inhalte.
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
name: Kann KI das? Sponsoring Agent
provenance_date: '2026-11-09'
provider_name: Kann KI das? Sponsoring Agent
provider_slug: kannkidas-de
slug: kannkidas-de-eligibility
source_date: '2026-11-09'
source_filename: kannkidas-de-eligibility.yml
source_heading: Eligibility
source_page: https://kannkidas.de/nutzungsbedingungen/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kann KI das? Sponsoring Agent\naid: kannkidas-de\nurl: https://kannkidas.de/nutzungsbedingungen/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Sponsorplätze richten sich ausschließlich an Unternehmer im Sinne des § 14 BGB\n- type: government\n  text: juristische Personen des öffentlichen Rechts und öffentlich-rechtliche Sondervermögen\nrestricted_uses:\n- summary: Prohibited ad content\n  text: Unzulässig sind insbesondere irreführende, rechtswidrige, diskriminierende oder schadsoftwarehaltige Inhalte\n    sowie Angebote für unerlaubte\
  \ Finanzprodukte, Glücksspiel, Waffen oder pornografische Inhalte.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kannkidas-de/eligibility/kannkidas-de-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Kann KI das? Sponsoring Agent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sponsoring
- Advertising
- Software Reviews
- Build vs Buy
- Search
- Agent-Native
- MCP
- A2A
- OAuth
- x402
- Stripe Checkout
- Germany
- Authentication
---
