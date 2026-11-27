---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Members residing outside the US may not be eligible for an income tax deduction for contributions to a Daffy fund.
  entity_types:
  - text: any individual 18 years or older, corporation, or trust may become a Daffy member, create a Daffy fund, or join an existing Daffy fund.
    type: individual
  - text: any individual 18 years or older, corporation, or trust may become a Daffy member, create a Daffy fund, or join an existing Daffy fund.
    type: business
  minimum_age:
    text: any individual 18 years or older, corporation, or trust may become a Daffy member
    value: '18'
  restricted_uses:
  - summary: No donations to non-US or private non-operating foundations
    text: 'Daffy does not permit members to recommend donations to: non-U.S. charitable organizations private foundations that are not classified as operating foundations'
  - summary: No donations benefiting disqualified persons
    text: Provide more than an incidental benefit to the member, or any of the aforementioned’s family or 35% controlled entity
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
name: Daffy
provenance_date: '2026-11-09'
provider_name: Daffy
provider_slug: daffy
slug: daffy-eligibility
source_date: '2026-11-09'
source_filename: daffy-eligibility.yml
source_heading: Eligibility
source_page: https://www.daffy.org/legal/agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Daffy\naid: daffy\nurl: https://www.daffy.org/legal/agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Members residing outside the US may not be eligible for an income tax deduction for contributions to a Daffy\n    fund.\nentity_types:\n- type: individual\n  text: any individual 18 years or older, corporation, or trust may become a Daffy member, create a Daffy fund,\n    or join an existing Daffy fund.\n- type: business\n  text: any individual 18 years or older, corporation, or trust may become a Daffy member, create a Daffy fund,\n    or join an existing\
  \ Daffy fund.\nrestricted_uses:\n- summary: No donations to non-US or private non-operating foundations\n  text: 'Daffy does not permit members to recommend donations to: non-U.S. charitable organizations private foundations\n    that are not classified as operating foundations'\n- summary: No donations benefiting disqualified persons\n  text: Provide more than an incidental benefit to the member, or any of the aforementioned’s family or 35% controlled\n    entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: any individual 18 years or older, corporation, or trust may become a Daffy member\n"
source_yaml_url: https://artifacts.apis.io/daffy/eligibility/daffy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Daffy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Charitable Giving
- Donor Advised Fund
- Non-Profit
- Wealth Management
- Investing
- Philanthropy
---
