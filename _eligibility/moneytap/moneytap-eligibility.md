---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: you, as a User, further represent that you are an Indian national having tax residency in India.
  entity_types:
  - text: You represent and warrant that you are competent and eligible to enter into a legally binding agreement and be bound by these T&Cs.
    type: individual
  - text: If you represent a company, partnership firm or sole proprietorship, you shall be eligible to access the App and avail of the features and facilities on its behalf only if you have been duly authorized by way of necessary corporate action
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or immoral use
    text: (c) use the App for any unlawful or immoral purpose.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: the User downloads the App, provides basic information and is either rejected or qualified for the Freo Pay Limit.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MoneyTap
provenance_date: '2026-11-10'
provider_name: MoneyTap
provider_slug: moneytap
slug: moneytap-eligibility
source_date: '2026-11-10'
source_filename: moneytap-eligibility.yml
source_heading: Eligibility
source_page: https://freo.money/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MoneyTap\naid: moneytap\nurl: https://freo.money/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: you, as a User, further represent that you are an Indian national having tax residency in India.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are competent and eligible to enter into a legally binding agreement\n    and be bound by these T&Cs.\n- type: business\n  text: If you represent a company, partnership firm or sole proprietorship, you shall be eligible to access the\n    App and avail of the features\
  \ and facilities on its behalf only if you have been duly authorized by way of necessary\n    corporate action\nrestricted_uses:\n- summary: Unlawful or immoral use\n  text: (c) use the App for any unlawful or immoral purpose.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: the User downloads the App, provides basic information and is either rejected or qualified for the Freo\n    Pay Limit.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moneytap/eligibility/moneytap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from MoneyTap's own page on 2026-11-10.
synthetic: false
tags:
- Personal Loans
- Credit Line
- Instant Loans
- Fintech
- RBI Regulated
- Consumer Credit
---
