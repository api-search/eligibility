---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Workspace plans (Team and Enterprise) are sold to business customers (näringsidkare).
    type: business
  - text: The Pro personal plan is sold to an individual engineer for their own use and may be a consumer purchase
    type: individual
  minimum_age:
    text: You must be at least 13, or the minimum age required where you live, to use Atomic Reps .
    value: '13'
  restricted_uses:
  - summary: Export control and sanctions
    text: Use the Service in violation of applicable export control or sanctions law (US, EU, UN, UK).
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
name: Atomic Reps AB
provenance_date: '2026-11-09'
provider_name: Atomic Reps AB
provider_slug: atomicreps-com
slug: atomicreps-com-eligibility
source_date: '2026-11-09'
source_filename: atomicreps-com-eligibility.yml
source_heading: Eligibility
source_page: https://atomicreps.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atomic Reps AB\naid: atomicreps-com\nurl: https://atomicreps.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Workspace plans (Team and Enterprise) are sold to business customers (näringsidkare).\n- type: individual\n  text: The Pro personal plan is sold to an individual engineer for their own use and may be a consumer purchase\nrestricted_uses:\n- summary: Export control and sanctions\n  text: Use the Service in violation of applicable export control or sanctions law (US, EU, UN, UK).\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13, or the minimum age required where you live, to use Atomic Reps .\n"
source_yaml_url: https://artifacts.apis.io/atomicreps-com/eligibility/atomicreps-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Atomic Reps AB's own page on 2026-11-09.
synthetic: false
tags:
- Developer Tools
- Education
- Artificial Intelligence
- Software Engineering
- Sweden
---
