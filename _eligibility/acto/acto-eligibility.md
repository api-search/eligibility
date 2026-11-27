---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: authorized user licences you purchase for the use of ACTO Suite
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: ACTO Suite is not fault-tolerant and is not designed or intended for use in hazardous environments requiring fail-safe performance
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
name: ACTO
provenance_date: '2026-11-09'
provider_name: ACTO
provider_slug: acto
slug: acto-eligibility
source_date: '2026-11-09'
source_filename: acto-eligibility.yml
source_heading: Eligibility
source_page: https://acto.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ACTO\naid: acto\nurl: https://acto.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: authorized user licences you purchase for the use of ACTO Suite\nrestricted_uses:\n- summary: High-risk activities\n  text: ACTO Suite is not fault-tolerant and is not designed or intended for use in hazardous environments requiring\n    fail-safe performance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acto/eligibility/acto-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ACTO's own page on 2026-11-09.
synthetic: false
tags:
- Life Sciences
- Pharmaceuticals
- Sales Enablement
- LMS
- Field Force Effectiveness
- Medical Affairs
- Commercial Excellence
- Training and Certification
- Omnichannel Engagement
- Artificial Intelligence
- Medical Devices
- Biotechnology
- Content Management
- Healthcare
---
