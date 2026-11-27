---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended solely for use by businesses and other organizations.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal, household or consumer use
    text: not for personal, household, or consumer purposes
  - summary: Restricted Content must be excluded from capture
    text: Customer agrees to exclude and is solely and fully responsible for configuring the Service to exclude any and all Restricted Content from being captured by Mouseflow
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
name: Mouseflow
provenance_date: '2026-11-10'
provider_name: Mouseflow
provider_slug: mouseflow
slug: mouseflow-eligibility
source_date: '2026-11-10'
source_filename: mouseflow-eligibility.yml
source_heading: Eligibility
source_page: https://mouseflow.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mouseflow\naid: mouseflow\nurl: https://mouseflow.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended solely for use by businesses and other organizations.\nrestricted_uses:\n- summary: No personal, household or consumer use\n  text: not for personal, household, or consumer purposes\n- summary: Restricted Content must be excluded from capture\n  text: Customer agrees to exclude and is solely and fully responsible for configuring the Service to exclude any\n    and all Restricted Content from being\
  \ captured by Mouseflow\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mouseflow/eligibility/mouseflow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Mouseflow's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
