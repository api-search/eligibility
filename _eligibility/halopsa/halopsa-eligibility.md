---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Where an entity or organisation purchases the Services or the Support Services for use by its employees
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or unauthorised use
    text: use the Services and/or its outputs unlawfully or in any manner not expressly authorized by this Agreement
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
name: HaloPSA
provenance_date: '2026-11-09'
provider_name: HaloPSA
provider_slug: halopsa
slug: halopsa-eligibility
source_date: '2026-11-09'
source_filename: halopsa-eligibility.yml
source_heading: Eligibility
source_page: https://www.usehalo.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HaloPSA\naid: halopsa\nurl: https://www.usehalo.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Where an entity or organisation purchases the Services or the Support Services for use by its employees\nrestricted_uses:\n- summary: Unlawful or unauthorised use\n  text: use the Services and/or its outputs unlawfully or in any manner not expressly authorized by this Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/halopsa/eligibility/halopsa-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from HaloPSA's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Workflow Automation
- ITSM
- Customer Service Management
- Enterprise Service Management
---
