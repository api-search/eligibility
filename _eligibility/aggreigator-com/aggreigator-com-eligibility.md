---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We provide Services only in states where we have determined we may lawfully do so
  entity_types:
  - text: A bona fide real estate investor, wholesaler, or licensed industry professional Seeking investment properties for business or investment purposes
    type: business
  minimum_age:
    text: You are at least 18 years old and have the legal capacity to enter into binding contracts.
    value: '18'
  restricted_uses:
  - summary: No owner-occupied residential financing
    text: NOT seeking owner-occupied residential financing or consumer mortgage products
  - summary: No deals marketed to owner-occupants
    text: Market Deals to owner-occupants or consumers through our Platform
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
name: AggREIgator
provenance_date: '2026-11-09'
provider_name: AggREIgator
provider_slug: aggreigator-com
slug: aggreigator-com-eligibility
source_date: '2026-11-09'
source_filename: aggreigator-com-eligibility.yml
source_heading: Eligibility
source_page: https://aggreigator.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AggREIgator\naid: aggreigator-com\nurl: https://aggreigator.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We provide Services only in states where we have determined we may lawfully do so\nentity_types:\n- type: business\n  text: A bona fide real estate investor, wholesaler, or licensed industry professional Seeking investment properties\n    for business or investment purposes\nrestricted_uses:\n- summary: No owner-occupied residential financing\n  text: NOT seeking owner-occupied residential financing or consumer mortgage products\n- summary: No deals marketed to owner-occupants\n\
  \  text: Market Deals to owner-occupants or consumers through our Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old and have the legal capacity to enter into binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/aggreigator-com/eligibility/aggreigator-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AggREIgator's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Wholesaling
- Platform
- Tools
- Finance
---
