---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: With respect to Customers located in the U.S., this Agreement shall be governed by and construed in accordance with the laws of the State of Delaware
  entity_types:
  - text: Customer must be a business, charitable organization or not-for-profit organization to use the Services.
    type: business
  - text: Customer must be a business, charitable organization or not-for-profit organization to use the Services.
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal business activity prohibited
    text: any business that is illegal or operates in support of illegal activity is prohibited from using the Services.
  - summary: Sanctioned persons prohibited
    text: Persons who appear on the U.S. Department of the Treasury, Office of Foreign Assets Control (OFAC), Specially Designated Nationals List (SDN)
  - summary: Personal consumer use prohibited
    text: The Services may not be used for individual consumer use.
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
name: Bench
provenance_date: '2026-11-09'
provider_name: Bench
provider_slug: bench
slug: bench-eligibility
source_date: '2026-11-09'
source_filename: bench-eligibility.yml
source_heading: Eligibility
source_page: https://www.bench.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bench\naid: bench\nurl: https://www.bench.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: With respect to Customers located in the U.S., this Agreement shall be governed by and construed in accordance\n    with the laws of the State of Delaware\nentity_types:\n- type: business\n  text: Customer must be a business, charitable organization or not-for-profit organization to use the Services.\n- type: nonprofit\n  text: Customer must be a business, charitable organization or not-for-profit organization to use the Services.\nrestricted_uses:\n- summary:\
  \ Illegal business activity prohibited\n  text: any business that is illegal or operates in support of illegal activity is prohibited from using the Services.\n- summary: Sanctioned persons prohibited\n  text: Persons who appear on the U.S. Department of the Treasury, Office of Foreign Assets Control (OFAC), Specially\n    Designated Nationals List (SDN)\n- summary: Personal consumer use prohibited\n  text: The Services may not be used for individual consumer use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bench/eligibility/bench-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 6 quoted statements, read from Bench's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Bookkeeping
- Small Business
- Software-as-a-Service
- Finance
---
