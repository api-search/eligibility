---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you open a User Account on behalf of a company, organization, or other entity, then (i) “you” includes you and that entity
    type: business
  minimum_age:
    text: Any use or access to the Service by anyone under 13 (or under 16 in Europe) is strictly prohibited
    value: '13'
  restricted_uses:
  - summary: Commercial solicitation prohibited
    text: using the Service for any commercial solicitation purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In certain instances, Magic may require you to provide proof of identity to create your account, or to access or use the Service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Magic
provenance_date: '2026-11-10'
provider_name: Magic
provider_slug: magic
slug: magic-eligibility
source_date: '2026-11-10'
source_filename: magic-eligibility.yml
source_heading: Eligibility
source_page: https://getmagic.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Magic\naid: magic\nurl: https://getmagic.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you open a User Account on behalf of a company, organization, or other entity, then (i) “you” includes\n    you and that entity\nrestricted_uses:\n- summary: Commercial solicitation prohibited\n  text: using the Service for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In certain instances, Magic may require you to provide proof of identity to create your account,\
  \ or to access\n    or use the Service\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under 13 (or under 16 in Europe) is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/magic/eligibility/magic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Magic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Virtual Assistant
- Outsourcing
- Productivity
- Staffing
- Concierge
- Business Services
---
