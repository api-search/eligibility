---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Certain Pellego Services may not be available in, or suitable for, certain countries or locales.
  minimum_age:
    text: We do not provide information or Services to minors. If You are under 18 You may only use this website with the active involvement of a parent, guardian or other supervising adult.
    value: '18'
  restricted_uses:
  - summary: No commercial or political solicitation
    text: Using the Website to advertise or solicit for commercial, political, religious purposes or otherwise
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
name: Pellego
provenance_date: '2026-11-10'
provider_name: Pellego
provider_slug: pellego
slug: pellego-eligibility
source_date: '2026-11-10'
source_filename: pellego-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.davinci.pellego.com/static/resources/TermsofService.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pellego\naid: pellego\nurl: https://cdn.davinci.pellego.com/static/resources/TermsofService.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Certain Pellego Services may not be available in, or suitable for, certain countries or locales.\nentity_types: []\nrestricted_uses:\n- summary: No commercial or political solicitation\n  text: Using the Website to advertise or solicit for commercial, political, religious purposes or otherwise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We do not provide information\
  \ or Services to minors. If You are under 18 You may only use this website with\n    the active involvement of a parent, guardian or other supervising adult.\n"
source_yaml_url: https://artifacts.apis.io/pellego/eligibility/pellego-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pellego's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- PropTech
- Brokerage
- Real Estate Investment
- Property Analysis
---
