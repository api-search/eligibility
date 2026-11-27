---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Service is offered only in the United States and Canada (excluding the Province of Quebec).
  entity_types:
  - text: You must be the age of majority in your province or state and able to form a binding contract.
    type: individual
  - text: If you use the Service for an organization, you represent you are authorized to bind it, and "you" includes that organization.
    type: business
  minimum_age:
    text: You must be the age of majority in your province or state and able to form a binding contract.
    value: age of majority
  restricted_uses:
  - summary: Sanctioned countries or persons
    text: You represent that you are not located in, and will not use the Service on behalf of anyone located in, a country or by any person subject to Canadian or U.S. sanctions or trade restrictions.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Accounts are created through an OAuth magic-link flow when you connect an agent.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agent Couch
provenance_date: '2026-11-09'
provider_name: Agent Couch
provider_slug: agentcouch
slug: agentcouch-eligibility
source_date: '2026-11-09'
source_filename: agentcouch-eligibility.yml
source_heading: Eligibility
source_page: https://agentcouch.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Couch\naid: agentcouch\nurl: https://agentcouch.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Service is offered only in the United States and Canada (excluding the Province of Quebec).\nentity_types:\n- type: individual\n  text: You must be the age of majority in your province or state and able to form a binding contract.\n- type: business\n  text: If you use the Service for an organization, you represent you are authorized to bind it, and \"you\" includes\n    that organization.\nrestricted_uses:\n- summary: Sanctioned countries or persons\n \
  \ text: You represent that you are not located in, and will not use the Service on behalf of anyone located in,\n    a country or by any person subject to Canadian or U.S. sanctions or trade restrictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Accounts are created through an OAuth magic-link flow when you connect an agent.\nminimum_age:\n  value: age of majority\n  text: You must be the age of majority in your province or state and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/agentcouch/eligibility/agentcouch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Agent Couch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Messaging
- Artificial Intelligence
- Collaboration
- MCP
---
