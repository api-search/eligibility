---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you register on behalf of a company, you represent and warrant that you have authority to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: Transmit personal data of children under 13 (or the relevant age of digital consent) or other sensitive personal data without a lawful basis.
    value: null
  restricted_uses:
  - summary: Export-controlled or sanctioned use
    text: Use the Service in jurisdictions or for export‑controlled purposes prohibited under Norwegian, EU or U.S. law.
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
name: Crunched
provenance_date: '2026-11-09'
provider_name: Crunched
provider_slug: crunched
slug: crunched-eligibility
source_date: '2026-11-09'
source_filename: crunched-eligibility.yml
source_heading: Eligibility
source_page: https://www.usecrunched.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crunched\naid: crunched\nurl: https://www.usecrunched.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you register on behalf of a company, you represent and warrant that you have authority to bind that organisation\n    to these Terms.\nrestricted_uses:\n- summary: Export-controlled or sanctioned use\n  text: Use the Service in jurisdictions or for export‑controlled purposes prohibited under Norwegian, EU or U.S.\n    law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n \
  \ value: null\n  text: Transmit personal data of children under 13 (or the relevant age of digital consent) or other sensitive\n    personal data without a lawful basis.\n"
source_yaml_url: https://artifacts.apis.io/crunched/eligibility/crunched-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Crunched's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Finance
- Excel
- Spreadsheets
- Financial Modeling
- Investment Banking
- Private Equity
- Management Consulting
- Productivity
---
