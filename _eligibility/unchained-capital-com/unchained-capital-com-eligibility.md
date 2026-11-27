---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must be a resident of one of the Loan Authorized States to apply for a Bitcoin Secured Loan or one of the Trading Desk Authorized States to use Trading Desk Services.
  entity_types:
  - text: To access and use the Site and the other Unchained Services, you must be at least 18 years of age.
    type: individual
  - text: If you are acting on behalf of an Organization, the following additional terms shall apply
    type: business
  minimum_age:
    text: To access and use the Site and the other Unchained Services, you must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Investment or profit-making use only
    text: Your use of the Unchained Site and the Unchained Services must at all times be for investment and/or other profit-making purposes.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Unchained conducts full anti-money laundering (AML) and know your customer (KYC) verification checks on users of the Unchained Services. In the case of an Organization, Unchained may conduct AML and KYC checks on the Organization itself
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Unchained Capital
provenance_date: '2026-11-10'
provider_name: Unchained Capital
provider_slug: unchained-capital-com
slug: unchained-capital-com-eligibility
source_date: '2026-11-10'
source_filename: unchained-capital-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.unchained.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unchained Capital\naid: unchained-capital-com\nurl: https://www.unchained.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You must be a resident of one of the Loan Authorized States to apply for a Bitcoin Secured Loan or one of\n    the Trading Desk Authorized States to use Trading Desk Services.\nentity_types:\n- type: individual\n  text: To access and use the Site and the other Unchained Services, you must be at least 18 years of age.\n- type: business\n  text: If you are acting on behalf of an Organization, the following additional terms\
  \ shall apply\nrestricted_uses:\n- summary: Investment or profit-making use only\n  text: Your use of the Unchained Site and the Unchained Services must at all times be for investment and/or other\n    profit-making purposes.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Unchained conducts full anti-money laundering (AML) and know your customer (KYC) verification checks on\n    users of the Unchained Services. In the case of an Organization, Unchained may conduct AML and KYC checks on\n    the Organization itself\nminimum_age:\n  value: '18'\n  text: To access and use the Site and the other Unchained Services, you must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/unchained-capital-com/eligibility/unchained-capital-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Unchained Capital's own page on 2026-11-10.
synthetic: false
tags:
- Bitcoin
- Financial Services
- Custody
- Investment
- Trust
---
