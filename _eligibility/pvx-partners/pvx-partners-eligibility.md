---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Services are primarily intended for businesses and their authorised representatives.
    type: business
  minimum_age:
    text: You must be at least 18 years old or the age of majority in your jurisdiction to access or use our websites or Services.
    value: '18'
  restricted_uses:
  - summary: Money laundering, sanctions evasion and fraud
    text: Use our Services for money laundering, terrorist financing, sanctions evasion, fraud or other prohibited activities
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: PvX may request additional information or documentation for identity verification, KYC, KYB, AML/CFT, sanctions screening, financing assessments, fraud prevention and regulatory compliance.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pvx Partners
provenance_date: '2026-11-10'
provider_name: Pvx Partners
provider_slug: pvx-partners
slug: pvx-partners-eligibility
source_date: '2026-11-10'
source_filename: pvx-partners-eligibility.yml
source_heading: Eligibility
source_page: https://pvxpartners.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pvx Partners\naid: pvx-partners\nurl: https://pvxpartners.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Our Services are primarily intended for businesses and their authorised representatives.\nrestricted_uses:\n- summary: Money laundering, sanctions evasion and fraud\n  text: Use our Services for money laundering, terrorist financing, sanctions evasion, fraud or other prohibited\n    activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: PvX may request additional information or documentation\
  \ for identity verification, KYC, KYB, AML/CFT, sanctions\n    screening, financing assessments, fraud prevention and regulatory compliance.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of majority in your jurisdiction to access or use our websites\n    or Services.\n"
source_yaml_url: https://artifacts.apis.io/pvx-partners/eligibility/pvx-partners-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Pvx Partners's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Financing
- User Acquisition
- Mobile Gaming
- Consumer App
- Analytics
- Venture Debt
---
