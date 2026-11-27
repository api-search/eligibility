---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for users who are at least eighteen (18) years old or the age of majority in their jurisdiction, whichever is older.
    type: individual
  minimum_age:
    text: The Service is intended for users who are at least eighteen (18) years old or the age of majority in their jurisdiction, whichever is older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Service only for lawful purposes and in accordance with these Terms.
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
name: Equity Residential
provenance_date: '2026-11-09'
provider_name: Equity Residential
provider_slug: equity-residential
slug: equity-residential-eligibility
source_date: '2026-11-09'
source_filename: equity-residential-eligibility.yml
source_heading: Eligibility
source_page: https://www.equityapartments.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Equity Residential\naid: equity-residential\nurl: https://www.equityapartments.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is intended for users who are at least eighteen (18) years old or the age of majority in their\n    jurisdiction, whichever is older.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Service only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: The Service is intended for users who are at least eighteen (18) years old or the age of majority in their\n    jurisdiction, whichever is older.\n"
source_yaml_url: https://artifacts.apis.io/equity-residential/eligibility/equity-residential-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Equity Residential's own page on 2026-11-09.
synthetic: false
tags:
- Apartments
- Fortune 500
- Housing
- Multifamily
- Property Management
- Real Estate
- REIT
---
