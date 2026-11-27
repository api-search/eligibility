---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Organization owners and administrators are responsible for who they invite, the roles they grant, and the content and assignments in their organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Assessment results not legal advice
    text: Assessment results are not legal, compliance, or employment advice.
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
name: AssessLane
provenance_date: '2026-11-09'
provider_name: AssessLane
provider_slug: assesslane-com
slug: assesslane-com-eligibility
source_date: '2026-11-09'
source_filename: assesslane-com-eligibility.yml
source_heading: Eligibility
source_page: https://assesslane.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AssessLane\naid: assesslane-com\nurl: https://assesslane.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Organization owners and administrators are responsible for who they invite, the roles they grant, and the\n    content and assignments in their organization.\nrestricted_uses:\n- summary: Assessment results not legal advice\n  text: Assessment results are not legal, compliance, or employment advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/assesslane-com/eligibility/assesslane-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AssessLane's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Team Assessments
- Software-as-a-Service
- MCP
- Productivity
---
