---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter a binding contract.
    type: individual
  - text: If you use Arcdeck for an organisation, you confirm you're allowed to accept these terms for it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter a binding contract.
    value: '18'
  restricted_uses:
  - summary: Illegal, fraudulent or abusive content
    text: Don't use Arcdeck to break the law, infringe others' rights, create content that is fraudulent, hateful or harassing
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
name: Arcdeck
provenance_date: '2026-11-09'
provider_name: Arcdeck
provider_slug: arcdeck-ai
slug: arcdeck-ai-eligibility
source_date: '2026-11-09'
source_filename: arcdeck-ai-eligibility.yml
source_heading: Eligibility
source_page: https://arcdeck.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arcdeck\naid: arcdeck-ai\nurl: https://arcdeck.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter a binding contract.\n- type: business\n  text: If you use Arcdeck for an organisation, you confirm you're allowed to accept these terms for it.\nrestricted_uses:\n- summary: Illegal, fraudulent or abusive content\n  text: Don't use Arcdeck to break the law, infringe others' rights, create content that is fraudulent, hateful\n    or harassing\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/arcdeck-ai/eligibility/arcdeck-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arcdeck's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Presentation
- Automation
- Software-as-a-Service
- Productivity
---
