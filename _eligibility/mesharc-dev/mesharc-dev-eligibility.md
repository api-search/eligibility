---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting for a company, you confirm you may bind it
    type: business
  minimum_age:
    text: You must be 18 or older, and must not be barred from using the service under the law that applies to you.
    value: '18'
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
name: mesharc-dev
provenance_date: '2026-11-10'
provider_name: mesharc-dev
provider_slug: mesharc-dev
slug: mesharc-dev-eligibility
source_date: '2026-11-10'
source_filename: mesharc-dev-eligibility.yml
source_heading: Eligibility
source_page: https://mesharc.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mesharc-dev\naid: mesharc-dev\nurl: https://mesharc.dev/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting for a company, you confirm you may bind it\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older, and must not be barred from using the service under the law that applies to you.\n"
source_yaml_url: https://artifacts.apis.io/mesharc-dev/eligibility/mesharc-dev-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from mesharc-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Imaging
- Data Management
- Healthcare
- Developer Tools
---
