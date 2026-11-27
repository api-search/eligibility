---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Brokers and Agents that have agreed to the subscription agreement, are also referred to herein as
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automated access to Services
    text: use any robot, spider, crawler, scraper, interface, scripts, or other automated means to collect information or otherwise interact with the Services;
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
name: Stellar MLS
provenance_date: '2026-11-10'
provider_name: Stellar MLS
provider_slug: stellar-mls
slug: stellar-mls-eligibility
source_date: '2026-11-10'
source_filename: stellar-mls-eligibility.yml
source_heading: Eligibility
source_page: https://www.stellarmls.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stellar MLS\naid: stellar-mls\nurl: https://www.stellarmls.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Brokers and Agents that have agreed to the subscription agreement, are also referred to herein as\nrestricted_uses:\n- summary: Automated access to Services\n  text: use any robot, spider, crawler, scraper, interface, scripts, or other automated means to collect information\n    or otherwise interact with the Services;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stellar-mls/eligibility/stellar-mls-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Stellar MLS's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- MLS
- RESO
- IDX
---
