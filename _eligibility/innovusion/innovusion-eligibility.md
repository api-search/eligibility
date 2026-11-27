---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Site.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated data (HIPAA, FISMA, GLBA)
    text: if your interactions would be subjected to such laws, you may not use this Site. You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: Seyond
provenance_date: '2026-11-09'
provider_name: Seyond
provider_slug: innovusion
slug: innovusion-eligibility
source_date: '2026-11-09'
source_filename: innovusion-eligibility.yml
source_heading: Eligibility
source_page: https://seyond.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seyond\naid: innovusion\nurl: https://seyond.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: a legally binding agreement made between you, whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Industry-regulated data (HIPAA, FISMA, GLBA)\n  text: if your interactions would be subjected to such\
  \ laws, you may not use this Site. You may not use the Site\n    in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Site.\n"
source_yaml_url: https://artifacts.apis.io/innovusion/eligibility/innovusion-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Seyond's own page on 2026-11-09.
synthetic: false
tags:
- Company
- LiDAR
- Sensors
- Autonomous Driving
- Intelligent Transportation
- Robotics
- Perception
- Smart Cities
- Automotive
- Hardware
---
