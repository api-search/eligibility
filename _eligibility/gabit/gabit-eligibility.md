---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years of age or have reached the age of majority in the jurisdiction in which You live or reside
    type: individual
  - text: 'If You represent a corporate entity or a firm: You have the full right, legal power and actual authority to bind such entity to these Terms'
    type: business
  minimum_age:
    text: You are at least 18 years of age or have reached the age of majority in the jurisdiction in which You live or reside
    value: '18'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: You further represent, warrant and assure that You shall not engage in any activity, host, display, upload, modify, publish, transmit, store, update or share any information or content that
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: To establish a User Account, You may be required to provide Gabit with certain personal information, including without limitation, Your first and last name, e-mail address, and phone numbers
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gabit
provenance_date: '2026-11-09'
provider_name: Gabit
provider_slug: gabit
slug: gabit-eligibility
source_date: '2026-11-09'
source_filename: gabit-eligibility.yml
source_heading: Eligibility
source_page: https://www.gabit.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gabit\naid: gabit\nurl: https://www.gabit.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years of age or have reached the age of majority in the jurisdiction in which You live\n    or reside\n- type: business\n  text: 'If You represent a corporate entity or a firm: You have the full right, legal power and actual authority\n    to bind such entity to these Terms'\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: You further represent, warrant and assure that You shall\
  \ not engage in any activity, host, display, upload,\n    modify, publish, transmit, store, update or share any information or content that\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: To establish a User Account, You may be required to provide Gabit with certain personal information, including\n    without limitation, Your first and last name, e-mail address, and phone numbers\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age or have reached the age of majority in the jurisdiction in which You live\n    or reside\n"
source_yaml_url: https://artifacts.apis.io/gabit/eligibility/gabit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Gabit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Wellness
- Wearables
- Smart Ring
- Fitness
- Nutrition
- Sleep
- Longevity
- Consumer Health
- Health Tracking
- Digital Health
---
