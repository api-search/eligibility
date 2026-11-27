---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the user — understood as the employee of a company, the administrator of a company, or the coworking space
    type: individual
  - text: the User/Company/Coworking
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: Use the site and its content only for purposes within the legal and regulatory framework, in accordance with morals, good customs, public order, and this agreement.
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
name: Worknmates
provenance_date: '2026-11-10'
provider_name: Worknmates
provider_slug: worknmates
slug: worknmates-eligibility
source_date: '2026-11-10'
source_filename: worknmates-eligibility.yml
source_heading: Eligibility
source_page: https://www.getoffi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Worknmates\naid: worknmates\nurl: https://www.getoffi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the user — understood as the employee of a company, the administrator of a company, or the coworking space\n- type: business\n  text: the User/Company/Coworking\nrestricted_uses:\n- summary: Lawful use only\n  text: Use the site and its content only for purposes within the legal and regulatory framework, in accordance\n    with morals, good customs, public order, and this agreement.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/worknmates/eligibility/worknmates-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Worknmates's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Co-Working
- Flexible Workspace
- Hybrid Work
- Marketplace
- Workplace
- Latin America
---
