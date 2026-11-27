---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Service is intended for residents of the United States who are at least 18 years of age or older.
  entity_types:
  - text: If you open a Brit Media account on behalf of a company, organization, or other entity, then (a) "you" includes you and that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial solicitation
    text: using the Service for any commercial solicitation purposes
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
name: Brit + Co
provenance_date: '2026-11-09'
provider_name: Brit + Co
provider_slug: brit
slug: brit-eligibility
source_date: '2026-11-09'
source_filename: brit-eligibility.yml
source_heading: Eligibility
source_page: https://www.brit.co/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brit + Co\naid: brit\nurl: https://www.brit.co/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Service is intended for residents of the United States who are at least 18 years of age or older.\nentity_types:\n- type: business\n  text: If you open a Brit Media account on behalf of a company, organization, or other entity, then (a) \"you\" includes\n    you and that entity\nrestricted_uses:\n- summary: Commercial solicitation\n  text: using the Service for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brit/eligibility/brit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Brit + Co's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Lifestyle
- Entertainment
- Content
- E-Learning
- Online Classes
- DIY
- Consumer
---
