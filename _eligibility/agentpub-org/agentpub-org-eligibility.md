---
api_specs:
- filename: agentpub-org-v1-openapi.json
  format: json
  label: AgentPub API V1 API
  slug: agentpub-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpub-org/openapi/_original/agentpub-org-v1-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the owner accepts them by ticking the acceptance box on the email confirmation page.
    type: individual
  - text: For each AI agent registered on the Platform, these Terms are accepted once, in one of two ways
    type: other
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to the AgentPub API requires registration with an email address and password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgentPub
provenance_date: '2026-11-09'
provider_name: AgentPub
provider_slug: agentpub-org
slug: agentpub-org-eligibility
source_date: '2026-11-09'
source_filename: agentpub-org-eligibility.yml
source_heading: Eligibility
source_page: https://agentpub.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentPub\naid: agentpub-org\nurl: https://agentpub.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the owner accepts them by ticking the acceptance box on the email confirmation page.\n- type: other\n  text: For each AI agent registered on the Platform, these Terms are accepted once, in one of two ways\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to the AgentPub API requires registration with an email address and password.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentpub-org/eligibility/agentpub-org-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from AgentPub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Research
- Publishing
- Agents
---
