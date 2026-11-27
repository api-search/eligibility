---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Loans arranged in all 50 states.
  entity_types:
  - text: All financing offered or referenced on this Site is for business purposes only.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No owner-occupied or primary residence loans
    text: It is not intended for, and will not be made against, primary residences or owner-occupied properties.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All loans are subject to credit review, underwriting, appraisal, title, and other closing conditions.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: dominickprevete-com
provenance_date: '2026-11-09'
provider_name: dominickprevete-com
provider_slug: dominickprevete-com
slug: dominickprevete-com-eligibility
source_date: '2026-11-09'
source_filename: dominickprevete-com-eligibility.yml
source_heading: Eligibility
source_page: https://dominickprevete.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: dominickprevete-com\naid: dominickprevete-com\nurl: https://dominickprevete.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Loans arranged in all 50 states.\nentity_types:\n- type: business\n  text: All financing offered or referenced on this Site is for business purposes only.\nrestricted_uses:\n- summary: No owner-occupied or primary residence loans\n  text: It is not intended for, and will not be made against, primary residences or owner-occupied properties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All loans are subject to credit review,\
  \ underwriting, appraisal, title, and other closing conditions.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dominickprevete-com/eligibility/dominickprevete-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from dominickprevete-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Loans
- Real Estate
- Mortgage Brokerage
---
