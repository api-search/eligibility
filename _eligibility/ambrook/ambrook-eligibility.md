---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Customer must be a legal resident of the United States and not on the United States Department of Treasury Specially Designated Nationals or Blocked Persons Lists to register and use the Services.
  entity_types:
  - text: Ambrook products and services are for business purposes only and are not to be used for personal, family, or household purposes.
    type: business
  minimum_age:
    text: Customer must at least 18 years old to open an Account.
    value: '18'
  restricted_uses:
  - summary: Illegal or restricted transactions
    text: Use the Site or Services for transactions involving (a) use of funds, grants or loans for unauthorized purposes or in violation of funding documents
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Ambrook will conduct, and/or will provide information to the Third-Party Provider to conduct, diligence on the Customer in connection with the process of onboarding Customer to a Wallet account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ambrook
provenance_date: '2026-11-09'
provider_name: Ambrook
provider_slug: ambrook
slug: ambrook-eligibility
source_date: '2026-11-09'
source_filename: ambrook-eligibility.yml
source_heading: Eligibility
source_page: https://ambrook.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ambrook\naid: ambrook\nurl: https://ambrook.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Customer must be a legal resident of the United States and not on the United States Department of Treasury\n    Specially Designated Nationals or Blocked Persons Lists to register and use the Services.\nentity_types:\n- type: business\n  text: Ambrook products and services are for business purposes only and are not to be used for personal, family,\n    or household purposes.\nrestricted_uses:\n- summary: Illegal or restricted transactions\n  text: Use the Site or Services for\
  \ transactions involving (a) use of funds, grants or loans for unauthorized purposes\n    or in violation of funding documents\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Ambrook will conduct, and/or will provide information to the Third-Party Provider to conduct, diligence\n    on the Customer in connection with the process of onboarding Customer to a Wallet account\nminimum_age:\n  value: '18'\n  text: Customer must at least 18 years old to open an Account.\n"
source_yaml_url: https://artifacts.apis.io/ambrook/eligibility/ambrook-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Ambrook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Agriculture
- Accounting
- Bookkeeping
- Payments
- Farm Management
- MCP
---
