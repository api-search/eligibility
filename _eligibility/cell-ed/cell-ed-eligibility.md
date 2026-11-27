---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 14.1 Individual Arbitration (For Individual Users)
    type: individual
  - text: If representing an entity, you confirm authority to bind that entity.
    type: business
  minimum_age:
    text: Users under 13 prohibited from using the Service
    value: '13'
  restricted_uses:
  - summary: No cheating
    text: Not using the Service for cheating
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
name: Cell-Ed
provenance_date: '2026-11-09'
provider_name: Cell-Ed
provider_slug: cell-ed
slug: cell-ed-eligibility
source_date: '2026-11-09'
source_filename: cell-ed-eligibility.yml
source_heading: Eligibility
source_page: https://www.cell-ed.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cell-Ed\naid: cell-ed\nurl: https://www.cell-ed.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 14.1 Individual Arbitration (For Individual Users)\n- type: business\n  text: If representing an entity, you confirm authority to bind that entity.\nrestricted_uses:\n- summary: No cheating\n  text: Not using the Service for cheating\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Users under 13 prohibited from using the Service\n"
source_yaml_url: https://artifacts.apis.io/cell-ed/eligibility/cell-ed-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cell-Ed's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Mobile Learning
- Workforce Development
- Microlearning
- SkillBuilding
- Company
---
