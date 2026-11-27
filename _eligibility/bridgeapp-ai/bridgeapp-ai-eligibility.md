---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users aren’t located in a country that is subject to a U.S. government embargo, or that has been designated by the U.S. government as a “terrorist-supporting” country
  entity_types:
  - text: The Service/BridgeApp is only intended for Users that do not qualify as Consumers, such as Business Users.
    type: business
  minimum_age:
    text: Users must be recognized as adult by applicable law
    value: adult
  restricted_uses:
  - summary: Consumers barred
    text: Users acting as "Consumers" under applicable EU law are not permitted to use the Service.
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
name: BridgeApp
provenance_date: '2026-11-09'
provider_name: BridgeApp
provider_slug: bridgeapp-ai
slug: bridgeapp-ai-eligibility
source_date: '2026-11-09'
source_filename: bridgeapp-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bridgeapp.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BridgeApp\naid: bridgeapp-ai\nurl: https://bridgeapp.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users aren’t located in a country that is subject to a U.S. government embargo, or that has been designated\n    by the U.S. government as a “terrorist-supporting” country\nentity_types:\n- type: business\n  text: The Service/BridgeApp is only intended for Users that do not qualify as Consumers, such as Business Users.\nrestricted_uses:\n- summary: Consumers barred\n  text: Users acting as \"Consumers\" under applicable EU law are not permitted to use the\
  \ Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adult\n  text: Users must be recognized as adult by applicable law\n"
source_yaml_url: https://artifacts.apis.io/bridgeapp-ai/eligibility/bridgeapp-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BridgeApp's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Workspace
- Team
- Collaboration
- Knowledge Base
---
