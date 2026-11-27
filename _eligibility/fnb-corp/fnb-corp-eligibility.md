---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful internet gambling transactions
    text: These restricted transactions are prohibited from being processed through your account or banking relationship with us.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your eligibility for particular products and services is subject to final determination and acceptance by FNB.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: F.N.B. Corporation
provenance_date: '2026-11-09'
provider_name: F.N.B. Corporation
provider_slug: fnb-corp
slug: fnb-corp-eligibility
source_date: '2026-11-09'
source_filename: fnb-corp-eligibility.yml
source_heading: Eligibility
source_page: https://www.fnb-online.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: F.N.B. Corporation\naid: fnb-corp\nurl: https://www.fnb-online.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful internet gambling transactions\n  text: These restricted transactions are prohibited from being processed through your account or banking relationship\n    with us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your eligibility for particular products and services is subject to final determination and acceptance by\n    FNB.\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/fnb-corp/eligibility/fnb-corp-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from F.N.B. Corporation's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Regional Bank
- Consumer Banking
- Commercial Banking
- Wealth Management
- Open Finance
---
