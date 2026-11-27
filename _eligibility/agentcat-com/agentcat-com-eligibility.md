---
api_specs:
- filename: agentcat-com-openapi-generated.yml
  format: yaml
  label: AgentCat API
  slug: agentcat-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcat-com/openapi/_ae-authored/agentcat-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual acting on behalf of an organization, you represent that you have authority to bind it.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: Use AgentCat for any illegal purposes
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
name: AgentCat
provenance_date: '2026-11-09'
provider_name: AgentCat
provider_slug: agentcat-com
slug: agentcat-com-eligibility
source_date: '2026-11-09'
source_filename: agentcat-com-eligibility.yml
source_heading: Eligibility
source_page: https://agentcat.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentCat\naid: agentcat-com\nurl: https://agentcat.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an individual acting on behalf of an organization, you represent that you have authority to bind\n    it.\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use AgentCat for any illegal purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentcat-com/eligibility/agentcat-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AgentCat's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Analytics
- Observability
- Agent Experience
- Company
---
