---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Argus is for businesses only. When you register, you confirm that you act for your business, not as a consumer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or unauthorised uploads
    text: upload award reports that you are not allowed to share with us, or anything illegal.
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
name: Argus
provenance_date: '2026-11-09'
provider_name: Argus
provider_slug: argus-ing
slug: argus-ing-eligibility
source_date: '2026-11-09'
source_filename: argus-ing-eligibility.yml
source_heading: Eligibility
source_page: https://argus.ing/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Argus\naid: argus-ing\nurl: https://argus.ing/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Argus is for businesses only. When you register, you confirm that you act for your business, not as a consumer.\nrestricted_uses:\n- summary: Illegal or unauthorised uploads\n  text: upload award reports that you are not allowed to share with us, or anything illegal.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/argus-ing/eligibility/argus-ing-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Argus's own page on 2026-11-09.
synthetic: false
tags:
- Tender
- Procurement
- Analytics
- Artificial Intelligence
- Belgium
---
