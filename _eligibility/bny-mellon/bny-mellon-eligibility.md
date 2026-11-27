---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Site, its contents and the Services are intended only for access and use by United States residents and are presented solely as a service to visitors and/or subscribers located in the United States of America and its territories.
  minimum_age:
    text: The AI Service(s) may not be used by anyone under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: AI Services age limit
    text: The AI Service(s) may not be used by anyone under 18 years of age.
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
name: BNY Mellon
provenance_date: '2026-11-09'
provider_name: BNY Mellon
provider_slug: bny-mellon
slug: bny-mellon-eligibility
source_date: '2026-11-09'
source_filename: bny-mellon-eligibility.yml
source_heading: Eligibility
source_page: https://www.bny.com/corporate/global/en/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BNY Mellon\naid: bny-mellon\nurl: https://www.bny.com/corporate/global/en/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Site, its contents and the Services are intended only for access and use by United States residents\n    and are presented solely as a service to visitors and/or subscribers located in the United States of America\n    and its territories.\nentity_types: []\nrestricted_uses:\n- summary: AI Services age limit\n  text: The AI Service(s) may not be used by anyone under 18 years of age.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The AI Service(s) may not be used by anyone under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/bny-mellon/eligibility/bny-mellon-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BNY Mellon's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Custody Bank
- Treasury Services
- Payments
- Digital Assets
- Open Finance
---
