---
api_specs:
- filename: agentlinkops-com-link-monitoring-and-evidence-api-openapi.yml
  format: yaml
  label: AgentLinkOps Link monitoring and evidence API
  slug: agentlinkops-com-link-monitoring-and-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentlinkops-com/openapi/agentlinkops-com-link-monitoring-and-evidence-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept them for a company or a client, you confirm you can bind it, and “you” means that organization.
    type: business
  - text: You must be at least 16 and able to enter a binding contract.
    type: individual
  minimum_age:
    text: You must be at least 16 and able to enter a binding contract.
    value: '16'
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
name: AgentLinkOps
provenance_date: '2026-11-09'
provider_name: AgentLinkOps
provider_slug: agentlinkops-com
slug: agentlinkops-com-eligibility
source_date: '2026-11-09'
source_filename: agentlinkops-com-eligibility.yml
source_heading: Eligibility
source_page: https://agentlinkops.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentLinkOps\naid: agentlinkops-com\nurl: https://agentlinkops.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept them for a company or a client, you confirm you can bind it, and “you” means that organization.\n- type: individual\n  text: You must be at least 16 and able to enter a binding contract.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 and able to enter a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/agentlinkops-com/eligibility/agentlinkops-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from AgentLinkOps's own page on 2026-11-09.
synthetic: false
tags:
- SEO
- Link Monitoring
- Backlink Analysis
- Agent Tools
- Web Analytics
- Company
---
