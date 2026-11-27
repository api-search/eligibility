---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform and Services are offered and available to users who are 18 years of age or older.
    type: individual
  - text: if you are authorized to act on behalf of a company, organization or other entity, the entity on behalf of which you act
    type: business
  - text: including as an authorized person of a nonprofit enrolled to the Platform
    type: nonprofit
  minimum_age:
    text: The Platform and Services are offered and available to users who are 18 years of age or older. If you are less than 18 years of age, you are only permitted to use the Services with parental or guardian consent and supervision.
    value: '18'
  restricted_uses:
  - summary: Discrimination and hate speech
    text: (vii) disseminate hate speech or dangerous speech, promote or incite violence online or offline.
  - summary: Advocacy against protected groups
    text: (iv) advocate against or deny the rights of historically underrepresented groups, including Black, brown, AAPI and Indigenous people
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
name: Give Lively
provenance_date: '2026-11-09'
provider_name: Give Lively
provider_slug: give-lively
slug: give-lively-eligibility
source_date: '2026-11-09'
source_filename: give-lively-eligibility.yml
source_heading: Eligibility
source_page: https://www.givelively.org/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Give Lively\naid: give-lively\nurl: https://www.givelively.org/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Platform and Services are offered and available to users who are 18 years of age or older.\n- type: business\n  text: if you are authorized to act on behalf of a company, organization or other entity, the entity on behalf\n    of which you act\n- type: nonprofit\n  text: including as an authorized person of a nonprofit enrolled to the Platform\nrestricted_uses:\n- summary: Discrimination and hate speech\n\
  \  text: (vii) disseminate hate speech or dangerous speech, promote or incite violence online or offline.\n- summary: Advocacy against protected groups\n  text: (iv) advocate against or deny the rights of historically underrepresented groups, including Black, brown,\n    AAPI and Indigenous people\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Platform and Services are offered and available to users who are 18 years of age or older. If you are\n    less than 18 years of age, you are only permitted to use the Services with parental or guardian consent and\n    supervision.\n"
source_yaml_url: https://artifacts.apis.io/give-lively/eligibility/give-lively-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Give Lively's own page on 2026-11-09.
synthetic: false
tags:
- Non-Profit
- Fundraising
- Platform
- Free
- Open Source
- Community
---
