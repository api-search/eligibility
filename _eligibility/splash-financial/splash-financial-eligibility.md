---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States.
  entity_types:
  - text: To qualify, a borrower must be a U.S. citizen or other eligible status and meet lender underwriting requirements.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal loan purpose limits
    text: Personal loans are solely for personal, family, or household purposes and are not permitted to be used to purchase or refinance the purchase of real estate, securities or other investments.
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
name: Splash Financial
provenance_date: '2026-11-10'
provider_name: Splash Financial
provider_slug: splash-financial
slug: splash-financial-eligibility
source_date: '2026-11-10'
source_filename: splash-financial-eligibility.yml
source_heading: Eligibility
source_page: https://www.splashfinancial.com/disclaimers/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Splash Financial\naid: splash-financial\nurl: https://www.splashfinancial.com/disclaimers/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States.\nentity_types:\n- type: individual\n  text: To qualify, a borrower must be a U.S. citizen or other eligible status and meet lender underwriting requirements.\nrestricted_uses:\n- summary: Personal loan purpose limits\n  text: Personal loans are solely for personal,\
  \ family, or household purposes and are not permitted to be used to\n    purchase or refinance the purchase of real estate, securities or other investments.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/splash-financial/eligibility/splash-financial-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Splash Financial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Lending
- Student Loans
- Personal Loans
- Marketplace
- Fintech
- Debt Consolidation
- Home Equity
---
