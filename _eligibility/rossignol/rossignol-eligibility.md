---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for users who are at least 13 years of age, and who are browsing the Site from the United States of America.
  entity_types:
  - text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Site.
    type: individual
  - text: whether personally or on behalf of an entity (“you”, “your”)
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Buying agents
    text: Use a buying agent or purchasing agent to make purchases on the Site
  - summary: Advertising or selling via the Site
    text: Use the Site to advertise or offer to sell goods and services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with the Site.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rossignol
provenance_date: '2026-11-10'
provider_name: Rossignol
provider_slug: rossignol
slug: rossignol-eligibility
source_date: '2026-11-10'
source_filename: rossignol-eligibility.yml
source_heading: Eligibility
source_page: https://www.rossignol.com/us-en/ls-terms-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rossignol\naid: rossignol\nurl: https://www.rossignol.com/us-en/ls-terms-conditions.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for users who are at least 13 years of age, and who are browsing the Site from the\n    United States of America.\nentity_types:\n- type: individual\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have\n    the permission of, and be directly supervised by, their parent or guardian to use the Site.\n- type: business\n  text: whether personally or on behalf of\
  \ an entity (“you”, “your”)\nrestricted_uses:\n- summary: Buying agents\n  text: Use a buying agent or purchasing agent to make purchases on the Site\n- summary: Advertising or selling via the Site\n  text: Use the Site to advertise or offer to sell goods and services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with the Site.\nminimum_age:\n  value: '13'\n  text: The Site is intended for users who are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/rossignol/eligibility/rossignol-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Rossignol's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Retail
- E-Commerce
- Sporting Goods
- Outdoor
- Apparel
- Winter Sports
---
