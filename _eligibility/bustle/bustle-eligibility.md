---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under age 18, you may not, under any circumstances or for any reason, use the Services.
    type: individual
  minimum_age:
    text: If you are under age 18, you may not, under any circumstances or for any reason, use the Services.
    value: '18'
  restricted_uses:
  - summary: commercial use of Content
    text: You shall not sell, license, rent, or otherwise use or exploit any Content for commercial use or in any way that violates any third party right.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may, in our sole discretion, refuse to offer the Services to any person or entity and change its eligibility criteria at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bustle
provenance_date: '2026-11-09'
provider_name: Bustle
provider_slug: bustle
slug: bustle-eligibility
source_date: '2026-11-09'
source_filename: bustle-eligibility.yml
source_heading: Eligibility
source_page: https://www.bdg.com/info/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bustle\naid: bustle\nurl: https://www.bdg.com/info/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under age 18, you may not, under any circumstances or for any reason, use the Services.\nrestricted_uses:\n- summary: commercial use of Content\n  text: You shall not sell, license, rent, or otherwise use or exploit any Content for commercial use or in any\n    way that violates any third party right.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may, in our sole discretion,\
  \ refuse to offer the Services to any person or entity and change its eligibility\n    criteria at any time.\nminimum_age:\n  value: '18'\n  text: If you are under age 18, you may not, under any circumstances or for any reason, use the Services.\n"
source_yaml_url: https://artifacts.apis.io/bustle/eligibility/bustle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Bustle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Media
- Digital Publishing
- Content
- Lifestyle
- Entertainment
- Advertising
- Consumer
---
