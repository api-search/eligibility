---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: be a valid existing UK legal entity registered at Companies House with full power and authority to carry out your business and use the Services on the Mimo Platform
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No fraudulent or illegal activity
    text: You warrant you will not create fraudulent accounts or commit any fraudulent, dishonest or illegal activities in relation to the Services.
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
name: Mimo
provenance_date: '2026-11-10'
provider_name: Mimo
provider_slug: mimo
slug: mimo-eligibility
source_date: '2026-11-10'
source_filename: mimo-eligibility.yml
source_heading: Eligibility
source_page: https://info.mimohq.com/hubfs/Mimo%20Terms%20of%20Service%20(03.03.26)%20.docx.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mimo\naid: mimo\nurl: https://info.mimohq.com/hubfs/Mimo%20Terms%20of%20Service%20(03.03.26)%20.docx.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: be a valid existing UK legal entity registered at Companies House with full power and authority to carry\n    out your business and use the Services on the Mimo Platform\nentity_types: []\nrestricted_uses:\n- summary: No fraudulent or illegal activity\n  text: You warrant you will not create fraudulent accounts or commit any fraudulent, dishonest or illegal activities\n    in relation to the Services.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mimo/eligibility/mimo-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Mimo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Cash Flow Management
- Accounting
- Bookkeeping
- Small Business
- B2B
---
