---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: Persons that are residents of the United States of America, including those who qualify as 'US Citizen', 'permanent resident', 'resident alien' or 'US Person' as per the law of the United States of America (each a “US Person”) and residents of other jurisdictions that do not or only limited tolerate the offering of financial or investment services to their citizens (a “Resident”) must not utilise the services of BUX.
  entity_types:
  - text: BUX will not provide its Services to persons under the age of 18 years.
    type: individual
  minimum_age:
    text: BUX will not provide its Services to persons under the age of 18 years.
    value: '18'
  restricted_uses:
  - summary: No orders by email
    text: Orders cannot be placed by email.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: BUX will provide its Services subject to the acceptance, onboarding and customer due diligence of the (prospective) Client.
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BUX
provenance_date: '2026-11-09'
provider_name: BUX
provider_slug: bux
slug: bux-eligibility
source_date: '2026-11-09'
source_filename: bux-eligibility.yml
source_heading: Eligibility
source_page: https://bux.com/documents/BUX-Client-Agreement-EN.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BUX\naid: bux\nurl: https://bux.com/documents/BUX-Client-Agreement-EN.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  text: Persons that are residents of the United States of America, including those who qualify as 'US Citizen',\n    'permanent resident', 'resident alien' or 'US Person' as per the law of the United States of America (each a\n    “US Person”) and residents of other jurisdictions that do not or only limited tolerate the offering of financial\n    or investment services to their citizens (a “Resident”) must not utilise the services of BUX.\nentity_types:\n\
  - type: individual\n  text: BUX will not provide its Services to persons under the age of 18 years.\nrestricted_uses:\n- summary: No orders by email\n  text: Orders cannot be placed by email.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: BUX will provide its Services subject to the acceptance, onboarding and customer due diligence of the (prospective)\n    Client.\nminimum_age:\n  value: '18'\n  text: BUX will not provide its Services to persons under the age of 18 years.\n"
source_yaml_url: https://artifacts.apis.io/bux/eligibility/bux-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from BUX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Investing
- Neobroker
- Brokerage
- Stocks
- ETFs
- Europe
- Wealth Management
---
