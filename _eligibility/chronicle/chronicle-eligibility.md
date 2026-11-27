---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: HIPAA / FISMA regulated interactions
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: GLBA-violating use
    text: You may not use the Site in a way that would violate the Gramm Leach-Bliley Act (GLBA).
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
name: Chronicle
provenance_date: '2026-11-09'
provider_name: Chronicle
provider_slug: chronicle
slug: chronicle-eligibility
source_date: '2026-11-09'
source_filename: chronicle-eligibility.yml
source_heading: Eligibility
source_page: https://chroniclehq.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chronicle\naid: chronicle\nurl: https://chroniclehq.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: HIPAA / FISMA regulated interactions\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: GLBA-violating\
  \ use\n  text: You may not use the Site in a way that would violate the Gramm Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/chronicle/eligibility/chronicle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Chronicle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Saas
- Presentations
- Artificial Intelligence
- Productivity
- Content Generation
- Agents
- MCP
- Developer API
---
