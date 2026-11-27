---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity ("you")
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Gramm-Leach-Bliley Act use
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  - summary: Industry-specific regulated interactions
    text: The Services are not tailored to comply with industry-specific regulations (Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
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
name: Shadowfax AI
provenance_date: '2026-11-10'
provider_name: Shadowfax AI
provider_slug: shadowfax
slug: shadowfax-eligibility
source_date: '2026-11-10'
source_filename: shadowfax-eligibility.yml
source_heading: Eligibility
source_page: https://shadowfax.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shadowfax AI\naid: shadowfax\nurl: https://shadowfax.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity (\"you\")\nrestricted_uses:\n- summary: Gramm-Leach-Bliley Act use\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\n- summary: Industry-specific regulated interactions\n  text: The Services are not tailored to comply with industry-specific regulations (Federal Information Security\n    Management Act (FISMA), etc.), so if your interactions\
  \ would be subjected to such laws, you may not use the\n    Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/shadowfax/eligibility/shadowfax-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Shadowfax AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Business Intelligence
- Artificial Intelligence
- Data
- Agentic Analytics
- Data Engineering
- Software-as-a-Service
---
