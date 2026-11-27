---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you must be an individual of at least 18 years of age, have a U.S. bank account, and reside in the United States or one of its territories.
  entity_types:
  - text: To use the Services you must be an individual of at least 18 years of age
    type: individual
  minimum_age:
    text: you must be an individual of at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Prohibited payments
    text: Using the Platform and/or Services to make the following types of payments is prohibited
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
name: iTrustCapital
provenance_date: '2026-11-09'
provider_name: iTrustCapital
provider_slug: itrustcapital
slug: itrustcapital-eligibility
source_date: '2026-11-09'
source_filename: itrustcapital-eligibility.yml
source_heading: Eligibility
source_page: https://www.itrustcapital.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iTrustCapital\naid: itrustcapital\nurl: https://www.itrustcapital.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you must be an individual of at least 18 years of age, have a U.S. bank account, and reside in the United\n    States or one of its territories.\nentity_types:\n- type: individual\n  text: To use the Services you must be an individual of at least 18 years of age\nrestricted_uses:\n- summary: Prohibited payments\n  text: Using the Platform and/or Services to make the following types of payments is prohibited\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be an individual of at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/itrustcapital/eligibility/itrustcapital-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from iTrustCapital's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Cryptocurrency
- Digital Assets
- Retirement
- Individual Retirement Accounts
- Precious Metals
- Custody
- Fintech
- Wealth Management
- Staking
---
