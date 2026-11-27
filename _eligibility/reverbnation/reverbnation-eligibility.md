---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU USE THE SITE AND THE SERVICES ACTING AS THE REPRESENTATIVE FOR AN ARTIST, BAND, GROUP, COMPANY, OR ENTITY, YOU REPRESENT THAT YOU HAVE THE LEGAL AUTHORITY TO BIND SUCH INDIVIDUAL OR ENTITY
    type: business
  minimum_age:
    text: The Site and Services are intended for use by persons 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use of Site Content
    text: you understand that the Site and Site Content is for your personal and non-commercial use only.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may accept or reject your user registration in our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ReverbNation
provenance_date: '2026-11-10'
provider_name: ReverbNation
provider_slug: reverbnation
slug: reverbnation-eligibility
source_date: '2026-11-10'
source_filename: reverbnation-eligibility.yml
source_heading: Eligibility
source_page: https://www.reverbnation.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ReverbNation\naid: reverbnation\nurl: https://www.reverbnation.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU USE THE SITE AND THE SERVICES ACTING AS THE REPRESENTATIVE FOR AN ARTIST, BAND, GROUP, COMPANY, OR\n    ENTITY, YOU REPRESENT THAT YOU HAVE THE LEGAL AUTHORITY TO BIND SUCH INDIVIDUAL OR ENTITY\nrestricted_uses:\n- summary: Personal non-commercial use of Site Content\n  text: you understand that the Site and Site Content is for your personal and non-commercial use only.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: true\n  text: We may accept or reject your user registration in our sole discretion.\nminimum_age:\n  value: '18'\n  text: The Site and Services are intended for use by persons 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/reverbnation/eligibility/reverbnation-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from ReverbNation's own page on 2026-11-10.
synthetic: false
tags:
- Music
- Distribution
- Promotion
- Artists
- Platform
- Company
---
