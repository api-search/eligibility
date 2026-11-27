---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The game is open to all Indian citizens of 18 years of age or above; residents of Tamil Nadu are not entitled to participate in the game.
  entity_types:
  - text: Membership into Ipsos Program is voluntary, open to all natural persons above the age of 18 years.
    type: individual
  minimum_age:
    text: open to all natural persons above the age of 18 years.
    value: '18'
  restricted_uses:
  - summary: Prohibited content in forums and uploads
    text: 'You agree not to host, display, upload, modify, publish, transmit, store, update or share any information that: belongs to another person and to which the you do not have any right'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Membership to the Program is at the sole discretion of Ipsos and it may refuse membership to any applicant without assigning any reasons.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CrownIT
provenance_date: '2026-11-09'
provider_name: CrownIT
provider_slug: crownit
slug: crownit-eligibility
source_date: '2026-11-09'
source_filename: crownit-eligibility.yml
source_heading: Eligibility
source_page: https://crownit.in/en/term
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CrownIT\naid: crownit\nurl: https://crownit.in/en/term\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The game is open to all Indian citizens of 18 years of age or above; residents of Tamil Nadu are not entitled\n    to participate in the game.\nentity_types:\n- type: individual\n  text: Membership into Ipsos Program is voluntary, open to all natural persons above the age of 18 years.\nrestricted_uses:\n- summary: Prohibited content in forums and uploads\n  text: 'You agree not to host, display, upload, modify, publish, transmit, store, update or share any information\n    that:\
  \ belongs to another person and to which the you do not have any right'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Membership to the Program is at the sole discretion of Ipsos and it may refuse membership to any applicant\n    without assigning any reasons.\nminimum_age:\n  value: '18'\n  text: open to all natural persons above the age of 18 years.\n"
source_yaml_url: https://artifacts.apis.io/crownit/eligibility/crownit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CrownIT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Market Research
- Consumer Insights
- Surveys
- Data Analytics
- India
---
