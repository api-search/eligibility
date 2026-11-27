---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use our application, you may need to register and provide certain information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: pepesto-com
provenance_date: '2026-11-10'
provider_name: pepesto-com
provider_slug: pepesto-com
slug: pepesto-com-eligibility
source_date: '2026-11-10'
source_filename: pepesto-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.pepesto.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pepesto-com\naid: pepesto-com\nurl: https://www.pepesto.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use our application, you may need to register and provide certain information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pepesto-com/eligibility/pepesto-com-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from pepesto-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Grocery
- European
- Pricing
---
