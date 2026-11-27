---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We offer our Services in select countries within the European Economic Area and the list may change in time.
  entity_types:
  - text: you are at least 18 years old and reside in a country where we offer our Services
    type: individual
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Residence restriction
    text: you must not open or maintain a Lightyear Account if you are physically resident in, or become resident in, a jurisdiction where our Services are not offered, restricted, or prohibited.
  - summary: No trading for third parties
    text: you must not use your account to trade on behalf of third parties, unless expressly permitted by us
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: you will provide any information we may reasonably request to verify your identity during the account setup
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lightyear
provenance_date: '2026-11-09'
provider_name: Lightyear
provider_slug: lightyear
slug: lightyear-eligibility
source_date: '2026-11-09'
source_filename: lightyear-eligibility.yml
source_heading: Eligibility
source_page: https://lightyear.com/en-eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lightyear\naid: lightyear\nurl: https://lightyear.com/en-eu/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: We offer our Services in select countries within the European Economic Area and the list may change in time.\nentity_types:\n- type: individual\n  text: you are at least 18 years old and reside in a country where we offer our Services\nrestricted_uses:\n- summary: Residence restriction\n  text: you must not open or maintain a Lightyear Account if you are physically resident in, or become resident\n    in, a jurisdiction where our Services are not offered,\
  \ restricted, or prohibited.\n- summary: No trading for third parties\n  text: you must not use your account to trade on behalf of third parties, unless expressly permitted by us\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: you will provide any information we may reasonably request to verify your identity during the account setup\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/lightyear/eligibility/lightyear-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Lightyear's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Investing
- Brokerage
- Stocks
- ETFs
- Fintech
- Wealth Management
- Europe
---
