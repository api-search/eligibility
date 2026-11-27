---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Crossover Website and may not accept the Terms of Use if you are a person barred from using services that Crossover provides under the laws of any country in which you are resident or from which you use the Services.
  minimum_age:
    text: To use the Communication Services you represent and warrant that you are at least of 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No advertising or solicitation in communication services
    text: Advertise or offer to sell or buy any goods or services for any business purpose
  - summary: No political campaigning in communication services
    text: Use Communication Services for political campaigning, recruiting votes, or soliciting support for legislative or other initiatives
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
name: Crossover Markets
provenance_date: '2026-11-09'
provider_name: Crossover Markets
provider_slug: crossover-markets
slug: crossover-markets-eligibility
source_date: '2026-11-09'
source_filename: crossover-markets-eligibility.yml
source_heading: Eligibility
source_page: https://crossovermarkets.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crossover Markets\naid: crossover-markets\nurl: https://crossovermarkets.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Crossover Website and may not accept the Terms of Use if you are a person barred from\n    using services that Crossover provides under the laws of any country in which you are resident or from which\n    you use the Services.\nentity_types: []\nrestricted_uses:\n- summary: No advertising or solicitation in communication services\n  text: Advertise or offer to sell or buy any goods or services for any business purpose\n- summary:\
  \ No political campaigning in communication services\n  text: Use Communication Services for political campaigning, recruiting votes, or soliciting support for legislative\n    or other initiatives\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Communication Services you represent and warrant that you are at least of 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/crossover-markets/eligibility/crossover-markets-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Crossover Markets's own page on 2026-11-09.
synthetic: false
tags:
- Digital Asset ECN
- Institutional Trading
- Execution‑Only Exchange
- Low‑Latency Matching
- Liquidity Pools
---
