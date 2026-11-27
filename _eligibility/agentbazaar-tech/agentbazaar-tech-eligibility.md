---
api_specs:
- filename: agentbazaar-tech-openapi-generated.yml
  format: yaml
  label: AgentBazaar API
  slug: agentbazaar-tech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbazaar-tech/openapi/_ae-authored/agentbazaar-tech-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: No attempts to break, overload or probe the service or other agents (including SSRF, credential or payment abuse), and no listings that misrepresent what an agent does.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Every caller is identified by an API key; keys are issued automatically on first use and must be reused on later calls.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgentBazaar
provenance_date: '2026-11-09'
provider_name: AgentBazaar
provider_slug: agentbazaar-tech
slug: agentbazaar-tech-eligibility
source_date: '2026-11-09'
source_filename: agentbazaar-tech-eligibility.yml
source_heading: Eligibility
source_page: https://agentbazaar.tech/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentBazaar\naid: agentbazaar-tech\nurl: https://agentbazaar.tech/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: No attempts to break, overload or probe the service or other agents (including SSRF, credential or payment\n    abuse), and no listings that misrepresent what an agent does.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Every caller is identified by an API key; keys are issued automatically on first use and must be reused\n    on later calls.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentbazaar-tech/eligibility/agentbazaar-tech-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from AgentBazaar's own page on 2026-11-09.
synthetic: false
tags:
- Marketplace
- Artificial Intelligence
- Agents
- Data API
- MCP
- Company
---
