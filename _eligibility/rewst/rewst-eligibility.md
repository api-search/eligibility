---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE USING THE SERVICES AS AN EMPLOYEE, CONTRACTOR, OR AGENT OF A CORPORATION, PARTNERSHIP, OR SIMILAR ENTITY, THEN YOU MUST BE AUTHORIZED TO SIGN FOR AND BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: it will not use, nor will it allow any third parties under its control to use, the Products or Services for high risk activities, such as the operation of nuclear facilities, air traffic control, or life support systems
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
name: Rewst
provenance_date: '2026-11-10'
provider_name: Rewst
provider_slug: rewst
slug: rewst-eligibility
source_date: '2026-11-10'
source_filename: rewst-eligibility.yml
source_heading: Eligibility
source_page: https://rewst.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rewst\naid: rewst\nurl: https://rewst.io/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE USING THE SERVICES AS AN EMPLOYEE, CONTRACTOR, OR AGENT OF A CORPORATION, PARTNERSHIP, OR SIMILAR\n    ENTITY, THEN YOU MUST BE AUTHORIZED TO SIGN FOR AND BIND SUCH ENTITY\nrestricted_uses:\n- summary: High-risk activities\n  text: it will not use, nor will it allow any third parties under its control to use, the Products or Services\n    for high risk activities, such as the operation of nuclear facilities, air traffic\
  \ control, or life support\n    systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rewst/eligibility/rewst-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Rewst's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DevOps
- Automation
- iPaaS
- RPA
- Workflow Automation
- MSP
- Integration
- Webhook
---
