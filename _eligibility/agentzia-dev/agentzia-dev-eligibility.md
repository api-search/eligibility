---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Service is offered only in the United States and Canada, excluding the Province of Quebec.
  entity_types:
  - text: If you use the Service for an organization, you represent that you are authorized to bind it, and "you" includes that organization.
    type: business
  minimum_age:
    text: You must be the age of majority in your province or state and able to form a binding contract.
    value: age of majority
  restricted_uses:
  - summary: Sanctioned persons or locations
    text: You represent that you are not subject to Canadian or United States sanctions or trade restrictions and will not use the Service for or on behalf of a prohibited person or location.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate account and billing information and keep it current.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Morphologic AI Inc.
provenance_date: '2026-11-09'
provider_name: Morphologic AI Inc.
provider_slug: agentzia-dev
slug: agentzia-dev-eligibility
source_date: '2026-11-09'
source_filename: agentzia-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.agentzia.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Morphologic AI Inc.\naid: agentzia-dev\nurl: https://www.agentzia.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Service is offered only in the United States and Canada, excluding the Province of Quebec.\nentity_types:\n- type: business\n  text: If you use the Service for an organization, you represent that you are authorized to bind it, and \"you\"\n    includes that organization.\nrestricted_uses:\n- summary: Sanctioned persons or locations\n  text: You represent that you are not subject to Canadian or United States sanctions or trade restrictions and\n\
  \    will not use the Service for or on behalf of a prohibited person or location.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide accurate account and billing information and keep it current.\nminimum_age:\n  value: age of majority\n  text: You must be the age of majority in your province or state and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/agentzia-dev/eligibility/agentzia-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Morphologic AI Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Geo
- Product Testing
- Generative AI
- Analytics
- Company
---
