---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: This agreement sets out the terms and conditions governing your use of the Voi app, Voi vehicles and related services in the United Kingdom.
  minimum_age:
    text: null
    value: null
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
name: Voi
provenance_date: '2026-11-10'
provider_name: Voi
provider_slug: voi
slug: voi-eligibility
source_date: '2026-11-10'
source_filename: voi-eligibility.yml
source_heading: Eligibility
source_page: https://www.voi.com/legal/user-agreement/uk
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voi\naid: voi\nurl: https://www.voi.com/legal/user-agreement/uk\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: This agreement sets out the terms and conditions governing your use of the Voi app, Voi vehicles and related\n    services in the United Kingdom.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/voi/eligibility/voi-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Voi's own page on 2026-11-10.
synthetic: false
tags:
- Micromobility
- E-Scooter
- E-Bikes
- Mobility As A Service
- Transportation
- GBFS
- MDS
- Sweden
- Mobility
---
