---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This Site is intended solely for users who are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Unsolicited mail and disruption
    text: (v) send unsolicited mail, including promotions and/or advertising of products and services.
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
name: Avant
provenance_date: '2026-11-09'
provider_name: Avant
provider_slug: avant
slug: avant-eligibility
source_date: '2026-11-09'
source_filename: avant-eligibility.yml
source_heading: Eligibility
source_page: https://www.avant.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avant\naid: avant\nurl: https://www.avant.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited mail and disruption\n  text: (v) send unsolicited mail, including promotions and/or advertising of products and services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Site is intended solely for users who are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/avant/eligibility/avant-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Avant's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lending
- Personal Loans
- Credit Cards
- Consumer Finance
- Banking
---
