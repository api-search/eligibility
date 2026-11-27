---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you confirm that you're at least 13 years old, or the applicable age of digital consent in your country, whichever is older.
    value: '13'
  restricted_uses:
  - summary: Harm to writers or readers
    text: Use our services to do harm to writers or readers
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
name: Ellipsus
provenance_date: '2026-11-09'
provider_name: Ellipsus
provider_slug: ellipsus
slug: ellipsus-eligibility
source_date: '2026-11-09'
source_filename: ellipsus-eligibility.yml
source_heading: Eligibility
source_page: https://ellipsus.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ellipsus\naid: ellipsus\nurl: https://ellipsus.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harm to writers or readers\n  text: Use our services to do harm to writers or readers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you confirm that you're at least 13 years old, or the applicable age of digital consent in your country,\n    whichever is older.\n"
source_yaml_url: https://artifacts.apis.io/ellipsus/eligibility/ellipsus-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Ellipsus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Collaborative Writing
- Writing Tools
- Content Creation
- Version Control
- Productivity
- Software-as-a-Service
---
