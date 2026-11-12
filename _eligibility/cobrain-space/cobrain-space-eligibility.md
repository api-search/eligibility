---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'An account belongs to one person: it is not shared.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful content and rights infringement
    text: Do not use Cobrain for unlawful content, to infringe other people’s rights, or to attack the service or other users.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'You need a real email address you can access: that is how you sign in and how you recover access.'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cobrain
provenance_date: '2026-11-09'
provider_name: Cobrain
provider_slug: cobrain-space
slug: cobrain-space-eligibility
source_date: '2026-11-09'
source_filename: cobrain-space-eligibility.yml
source_heading: Eligibility
source_page: https://cobrain.space/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cobrain\naid: cobrain-space\nurl: https://cobrain.space/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'An account belongs to one person: it is not shared.'\nrestricted_uses:\n- summary: Unlawful content and rights infringement\n  text: Do not use Cobrain for unlawful content, to infringe other people’s rights, or to attack the service or\n    other users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'You need a real email address you can access: that is how you sign in and how you recover access.'\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cobrain-space/eligibility/cobrain-space-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Cobrain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Memory
- Model Context Protocol
- MCP Server
- Knowledge Management
- Markdown
- Note Taking
- Collaboration
- Artificial Intelligence
---
