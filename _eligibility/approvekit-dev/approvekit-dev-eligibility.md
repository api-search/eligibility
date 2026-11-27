---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ApproveKit is for professionals and businesses. You must be at least 18
    type: individual
  - text: If you use ApproveKit for a company, you confirm you are authorized to bind it.
    type: business
  minimum_age:
    text: You must be at least 18
    value: '18'
  restricted_uses:
  - summary: No misleading reviewers or users
    text: You may not use it to mislead a platform reviewer or an end user
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
name: ApproveKit
provenance_date: '2026-11-09'
provider_name: ApproveKit
provider_slug: approvekit-dev
slug: approvekit-dev-eligibility
source_date: '2026-11-09'
source_filename: approvekit-dev-eligibility.yml
source_heading: Eligibility
source_page: https://approvekit.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ApproveKit\naid: approvekit-dev\nurl: https://approvekit.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: ApproveKit is for professionals and businesses. You must be at least 18\n- type: business\n  text: If you use ApproveKit for a company, you confirm you are authorized to bind it.\nrestricted_uses:\n- summary: No misleading reviewers or users\n  text: You may not use it to mislead a platform reviewer or an end user\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18\n"
source_yaml_url: https://artifacts.apis.io/approvekit-dev/eligibility/approvekit-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ApproveKit's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Mobile
- App Store
- Compliance
- Automation
---
