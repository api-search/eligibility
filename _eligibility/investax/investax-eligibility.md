---
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - US
    - IR
    - MM
    - KP
    served: []
    text: InvestaX currently does not accept persons or entities from the U.S. (except Issuers), Iran, Myanmar, Democratic People's Republic of Korea and any sanctioned country or any countries that InvestaX may specify, at its sole discretion, as Investors. InvestaX also does not accept any U.S. tax residents.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use unlawful in one's jurisdiction
    text: The Website and/or Services is prohibited for any person who is a citizen, or resident of, or located in any jurisdiction where the use of the Website or Services would be unlawful or contrary to Applicable Laws and Regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
- IR
- MM
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: InvestaX
provenance_date: '2026-11-09'
provider_name: InvestaX
provider_slug: investax
slug: investax-eligibility
source_date: '2026-11-09'
source_filename: investax-eligibility.yml
source_heading: Eligibility
source_page: https://investax.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: InvestaX\naid: investax\nurl: https://investax.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  - IR\n  - MM\n  - KP\n  text: InvestaX currently does not accept persons or entities from the U.S. (except Issuers), Iran, Myanmar, Democratic\n    People's Republic of Korea and any sanctioned country or any countries that InvestaX may specify, at its sole\n    discretion, as Investors. InvestaX also does not accept any U.S. tax residents.\nentity_types: []\nrestricted_uses:\n- summary: Use unlawful in one's jurisdiction\n  text: The Website and/or Services\
  \ is prohibited for any person who is a citizen, or resident of, or located in\n    any jurisdiction where the use of the Website or Services would be unlawful or contrary to Applicable Laws and\n    Regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/investax/eligibility/investax-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from InvestaX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tokenization
- Digital Securities
- Real World Assets
- Blockchain
- Fintech
- Capital Markets
- Financial Services
---
