---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: the Applicant must be a UK resident (but cannot be a US Person for tax purposes)
  entity_types:
  - text: Non-Limited Business – A sole trader resident in the UK, or a partnership established in the UK.
    type: business
  - text: trusts, not-for-profit organisations or government agencies incorporated in the UK
    type: nonprofit
  minimum_age:
    text: each person with access to the Account or Card is 18 years old or more and resident in the UK
    value: '18'
  restricted_uses:
  - summary: Prohibited activity or purpose
    text: The Card must not be used for any Prohibited Activity or Prohibited Purpose.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: We will accept or reject your application at our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ANNA Money
provenance_date: '2026-11-09'
provider_name: ANNA Money
provider_slug: anna-money
slug: anna-money-eligibility
source_date: '2026-11-09'
source_filename: anna-money-eligibility.yml
source_heading: Eligibility
source_page: https://anna.money/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ANNA Money\naid: anna-money\nurl: https://anna.money/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: the Applicant must be a UK resident (but cannot be a US Person for tax purposes)\nentity_types:\n- type: business\n  text: Non-Limited Business – A sole trader resident in the UK, or a partnership established in the UK.\n- type: nonprofit\n  text: trusts, not-for-profit organisations or government agencies incorporated in the UK\nrestricted_uses:\n- summary: Prohibited activity or purpose\n  text: The Card must not be used for any Prohibited\
  \ Activity or Prohibited Purpose.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: We will accept or reject your application at our sole discretion.\nminimum_age:\n  value: '18'\n  text: each person with access to the Account or Card is 18 years old or more and resident in the UK\n"
source_yaml_url: https://artifacts.apis.io/anna-money/eligibility/anna-money-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from ANNA Money's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- Fintech
- Business Account
- Open Banking
- PSD2
- Account Information
- Payments
- E-Money
- United Kingdom
- Small Business
---
