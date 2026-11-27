---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to create an Astryke Hub account.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to create an Astryke Hub account.
    value: '13'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: you must not use Astryke to store or transmit unlawful content, malicious code, or material that infringes someone else’s rights.
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
name: Astryke
provenance_date: '2026-11-09'
provider_name: Astryke
provider_slug: astryke-com
slug: astryke-com-eligibility
source_date: '2026-11-09'
source_filename: astryke-com-eligibility.yml
source_heading: Eligibility
source_page: https://astryke.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astryke\naid: astryke-com\nurl: https://astryke.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to create an Astryke Hub account.\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: you must not use Astryke to store or transmit unlawful content, malicious code, or material that infringes\n    someone else’s rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to\
  \ create an Astryke Hub account.\n"
source_yaml_url: https://artifacts.apis.io/astryke-com/eligibility/astryke-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Astryke's own page on 2026-11-09.
synthetic: false
tags:
- Game Development
- Indie Tools
- Pixel Art
- Audio Generation
- Free Widgets
---
