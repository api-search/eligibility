---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using it for an organisation, you are confirming you may accept on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account to connect.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AmlakIntel
provenance_date: '2026-11-09'
provider_name: AmlakIntel
provider_slug: amlakintel-com
slug: amlakintel-com-eligibility
source_date: '2026-11-09'
source_filename: amlakintel-com-eligibility.yml
source_heading: Eligibility
source_page: https://amlakintel.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AmlakIntel\naid: amlakintel-com\nurl: https://amlakintel.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using it for an organisation, you are confirming you may accept on its behalf.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need an account to connect.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/amlakintel-com/eligibility/amlakintel-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from AmlakIntel's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Artificial Intelligence
- Property Data
- Gulf
- ChatGPT
---
