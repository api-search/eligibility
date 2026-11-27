---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: It can be accessed from all Canadian Provinces and Territories, as well as from other countries around the world.
  entity_types:
  - text: Certain portions of the website relating to online banking may be accessed only by Conexus members who have enrolled in the services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized copying or reuse of content
    text: you may not copy, reproduce, modify, republish, upload, post, transmit, sell, license, distribute or otherwise exploit any documents or information from the website
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
name: Conexus Credit Union
provenance_date: '2026-11-09'
provider_name: Conexus Credit Union
provider_slug: conexus-credit-union
slug: conexus-credit-union-eligibility
source_date: '2026-11-09'
source_filename: conexus-credit-union-eligibility.yml
source_heading: Eligibility
source_page: https://www.conexus.ca/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conexus Credit Union\naid: conexus-credit-union\nurl: https://www.conexus.ca/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: It can be accessed from all Canadian Provinces and Territories, as well as from other countries around the\n    world.\nentity_types:\n- type: individual\n  text: Certain portions of the website relating to online banking may be accessed only by Conexus members who have\n    enrolled in the services\nrestricted_uses:\n- summary: Unauthorized copying or reuse of content\n  text: you may not copy, reproduce, modify, republish, upload, post, transmit,\
  \ sell, license, distribute or otherwise\n    exploit any documents or information from the website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/conexus-credit-union/eligibility/conexus-credit-union-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Conexus Credit Union's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- Canada
- Credit Union
- Cooperative
- Saskatchewan
- Open Banking
---
