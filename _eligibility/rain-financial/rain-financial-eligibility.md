---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: U.S. persons, including U.S. nationals, U.S. residents, or any individuals accessing the Platform from within the United States or outside the United States, are strictly prohibited from using the Platform or creating an account.
  entity_types:
  - text: Your Account is personal and will only be used by you
    type: individual
  - text: if you are registering to use the Services on behalf of a legal Entity, Person or legal arrangement
    type: business
  minimum_age:
    text: You must be of legal age in your country of residence, or at least 18 years old if residing in the UAE, to form a binding contract with Rain
    value: '18'
  restricted_uses:
  - summary: Prohibited Use
    text: use our Services to pay for, support or otherwise engage in any illegal gambling activities; fraud; money-laundering; or terrorist activities; or other illegal activities
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Your rights to access and use the Services will not take effect until we have notified you that we have completed our checks, confirmed your identity and confirmed your right to access and use the Services.
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rain Financial
provenance_date: '2026-11-10'
provider_name: Rain Financial
provider_slug: rain-financial
slug: rain-financial-eligibility
source_date: '2026-11-10'
source_filename: rain-financial-eligibility.yml
source_heading: Eligibility
source_page: https://www.rain.com/legal/rain-user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rain Financial\naid: rain-financial\nurl: https://www.rain.com/legal/rain-user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  text: U.S. persons, including U.S. nationals, U.S. residents, or any individuals accessing the Platform from within\n    the United States or outside the United States, are strictly prohibited from using the Platform or creating\n    an account.\nentity_types:\n- type: individual\n  text: Your Account is personal and will only be used by you\n- type: business\n  text: if you are registering to use the Services on behalf of a legal\
  \ Entity, Person or legal arrangement\nrestricted_uses:\n- summary: Prohibited Use\n  text: use our Services to pay for, support or otherwise engage in any illegal gambling activities; fraud; money-laundering;\n    or terrorist activities; or other illegal activities\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Your rights to access and use the Services will not take effect until we have notified you that we have\n    completed our checks, confirmed your identity and confirmed your right to access and use the Services.\nminimum_age:\n  value: '18'\n  text: You must be of legal age in your country of residence, or at least 18 years old if residing in the UAE,\n    to form a binding contract with Rain\n"
source_yaml_url: https://artifacts.apis.io/rain-financial/eligibility/rain-financial-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Rain Financial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Cryptocurrency Exchange
- Digital Assets
- Bitcoin
- Financial Services
- Fintech
- Trading
- Custody
- MENA
- Bahrain
---
