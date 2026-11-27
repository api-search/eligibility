---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform and Services are available only to, and may only be used by, firms, businesses, entities, organizations and individuals able to form legally binding contracts under applicable law.
    type: business
  - text: The Platform and Services are available only to, and may only be used by, firms, businesses, entities, organizations and individuals able to form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: you represent and warrant that you are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Investors and lenders must be Accredited Investors
    text: In order to use the Platform as an investor or lender, you must be an “Accredited Investor,” and you hereby represent and warrant that you are an Accredited Investor.
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
name: Axial Networks
provenance_date: '2026-11-09'
provider_name: Axial Networks
provider_slug: axial
slug: axial-eligibility
source_date: '2026-11-09'
source_filename: axial-eligibility.yml
source_heading: Eligibility
source_page: https://www.axial.net/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Axial Networks\naid: axial\nurl: https://www.axial.net/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Platform and Services are available only to, and may only be used by, firms, businesses, entities, organizations\n    and individuals able to form legally binding contracts under applicable law.\n- type: individual\n  text: The Platform and Services are available only to, and may only be used by, firms, businesses, entities, organizations\n    and individuals able to form legally binding contracts\
  \ under applicable law.\nrestricted_uses:\n- summary: Investors and lenders must be Accredited Investors\n  text: In order to use the Platform as an investor or lender, you must be an “Accredited Investor,” and you hereby\n    represent and warrant that you are an Accredited Investor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/axial/eligibility/axial-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Axial Networks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mergers and Acquisitions
- Private Capital
- Deal Sourcing
- Financial Services
- Middle Market
- Investment Banking
- Marketplace
---
