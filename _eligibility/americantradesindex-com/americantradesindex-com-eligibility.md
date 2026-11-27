---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A Pro plan is for one person; a team of 2 or more people needs an Enterprise plan.
    type: individual
  - text: Business contacts are for your own organization's business outreach only.
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: FCRA and eligibility decisions
    text: You agree that you will not use the Service, in whole or in part, as a factor in establishing an individual's eligibility for credit, insurance, employment, housing or tenant screening
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
name: American Trades Index
provenance_date: '2026-11-09'
provider_name: American Trades Index
provider_slug: americantradesindex-com
slug: americantradesindex-com-eligibility
source_date: '2026-11-09'
source_filename: americantradesindex-com-eligibility.yml
source_heading: Eligibility
source_page: https://americantradesindex.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: American Trades Index\naid: americantradesindex-com\nurl: https://americantradesindex.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A Pro plan is for one person; a team of 2 or more people needs an Enterprise plan.\n- type: business\n  text: Business contacts are for your own organization's business outreach only.\nrestricted_uses:\n- summary: FCRA and eligibility decisions\n  text: You agree that you will not use the Service, in whole or in part, as a factor in establishing an individual's\n    eligibility for credit,\
  \ insurance, employment, housing or tenant screening\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/americantradesindex-com/eligibility/americantradesindex-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from American Trades Index's own page on 2026-11-09.
synthetic: false
tags:
- Construction
- Leads
- Permits
- Bids
- Awards
---
