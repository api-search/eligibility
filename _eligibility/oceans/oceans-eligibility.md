---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THIS SITE IS OFFERED AND AVAILABLE TO USERS WHO ARE 16 YEARS OF AGE OR OLDER.
    type: individual
  minimum_age:
    text: THIS SITE IS OFFERED AND AVAILABLE TO USERS WHO ARE 16 YEARS OF AGE OR OLDER.
    value: '16'
  restricted_uses:
  - summary: Unlawful use
    text: Use the Site in any way that violates federal, state, local, or international law or regulation;
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
name: Oceans
provenance_date: '2026-11-10'
provider_name: Oceans
provider_slug: oceans
slug: oceans-eligibility
source_date: '2026-11-10'
source_filename: oceans-eligibility.yml
source_heading: Eligibility
source_page: https://oceanshealthcare.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oceans\naid: oceans\nurl: https://oceanshealthcare.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: THIS SITE IS OFFERED AND AVAILABLE TO USERS WHO ARE 16 YEARS OF AGE OR OLDER.\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the Site in any way that violates federal, state, local, or international law or regulation;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: THIS SITE IS OFFERED AND AVAILABLE TO USERS WHO ARE 16 YEARS OF AGE OR OLDER.\n"
source_yaml_url: https://artifacts.apis.io/oceans/eligibility/oceans-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Oceans's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Behavioral Health
- Mental Health
- Psychiatric Hospitals
- Outpatient
- Telehealth
- Veterans Care
---
