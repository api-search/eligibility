---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are not a resident of the United States and you use a Website or the Services, you understand and agree that you are doing so on your own initiative and at your own risk.
  entity_types:
  - text: The Services are intended for legal use by individuals 13 years of age and older.
    type: individual
  minimum_age:
    text: The Services are intended for legal use by individuals 13 years of age and older.
    value: '13'
  restricted_uses:
  - summary: Prohibited uses
    text: Is unlawful, illegal, fraudulent, harmful, harassing, abusive, tortious, defamatory, threatening, invasive of another’s privacy
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Approval of your request to establish an Account will be in Guild’s sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Guild
provenance_date: '2026-11-09'
provider_name: Guild
provider_slug: guild
slug: guild-eligibility
source_date: '2026-11-09'
source_filename: guild-eligibility.yml
source_heading: Eligibility
source_page: https://guild.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Guild\naid: guild\nurl: https://guild.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are not a resident of the United States and you use a Website or the Services, you understand and\n    agree that you are doing so on your own initiative and at your own risk.\nentity_types:\n- type: individual\n  text: The Services are intended for legal use by individuals 13 years of age and older.\nrestricted_uses:\n- summary: Prohibited uses\n  text: Is unlawful, illegal, fraudulent, harmful, harassing, abusive, tortious, defamatory, threatening, invasive\n    of another’s\
  \ privacy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Approval of your request to establish an Account will be in Guild’s sole discretion.\nminimum_age:\n  value: '13'\n  text: The Services are intended for legal use by individuals 13 years of age and older.\n"
source_yaml_url: https://artifacts.apis.io/guild/eligibility/guild-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Guild's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Education
- Workforce Development
- Employee Benefits
- Upskilling
- Career Mobility
- Learning and Development
- Human Resources
- Software-as-a-Service
---
