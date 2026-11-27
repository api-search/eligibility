---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We offer our Services in select countries within the European Economic Area and the list may change in time.
  minimum_age:
    text: you are at least 18 years old and reside in a country where we offer our Services
    value: '18'
  restricted_uses:
  - summary: Market Data limited to own assets
    text: By accessing Market Data, you represent and warrant that you are doing so solely to manage your own assets or make your own investment decisions, and not to manage assets on behalf of third parties
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: you authorise Lightyear or third parties to verify your identity and check for fraud.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lightyear
provenance_date: '2026-11-09'
provider_name: Lightyear
provider_slug: golightyear-com
slug: golightyear-com-eligibility
source_date: '2026-11-09'
source_filename: golightyear-com-eligibility.yml
source_heading: Eligibility
source_page: https://lightyear.com/en-eu/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lightyear\naid: golightyear-com\nurl: https://lightyear.com/en-eu/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: We offer our Services in select countries within the European Economic Area and the list may change in time.\nentity_types: []\nrestricted_uses:\n- summary: Market Data limited to own assets\n  text: By accessing Market Data, you represent and warrant that you are doing so solely to manage your own assets\n    or make your own investment decisions, and not to manage assets on behalf of third parties\nverification:\n  kyc: true\n  kyb: null\n \
  \ approval_required: null\n  text: you authorise Lightyear or third parties to verify your identity and check for fraud.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old and reside in a country where we offer our Services\n"
source_yaml_url: https://artifacts.apis.io/golightyear-com/eligibility/golightyear-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Lightyear's own page on 2026-11-09.
synthetic: false
tags:
- Investing
- Savings
- Stocks
- ETFs
- Cryptocurrency
---
