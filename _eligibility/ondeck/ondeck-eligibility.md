---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You must be at least 13 years of age to use our Services. By accepting these Terms and Conditions you represent and warrant that you: (a) are at least 18 years of age'
    type: individual
  minimum_age:
    text: You must be at least 13 years of age to use our Services.
    value: '13'
  restricted_uses:
  - summary: Commercial use of Services
    text: Sell, resell or commercially use our Services;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: ODF reserves the right in its sole discretion to accept or decline to accept any applicant or guest into an ODF Program after conducting an evaluation by means such as applications and interviews.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OnDeck
provenance_date: '2026-11-10'
provider_name: OnDeck
provider_slug: ondeck
slug: ondeck-eligibility
source_date: '2026-11-10'
source_filename: ondeck-eligibility.yml
source_heading: Eligibility
source_page: https://joinodf.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OnDeck\naid: ondeck\nurl: https://joinodf.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You must be at least 13 years of age to use our Services. By accepting these Terms and Conditions you represent\n    and warrant that you: (a) are at least 18 years of age'\nrestricted_uses:\n- summary: Commercial use of Services\n  text: Sell, resell or commercially use our Services;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: ODF reserves the right in its sole discretion to accept or\
  \ decline to accept any applicant or guest into\n    an ODF Program after conducting an evaluation by means such as applications and interviews.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/ondeck/eligibility/ondeck-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from OnDeck's own page on 2026-11-10.
synthetic: false
tags:
- Small Business Lending
- Fintech
- Loans
- Credit Scoring
- Business Health
- Term Loans
- Line of Credit
- Loan Origination
---
