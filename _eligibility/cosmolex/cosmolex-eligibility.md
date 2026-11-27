---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: All usage prices are valid for the U.S. and Canada only. Please inquire about rates in other locations.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No emergency services use
    text: Using CosmoLex numbers to provide emergency services, such as 911-types of communication – Inbound and outbound communications between emergency service providers and end users are explicitly not permitted on CosmoLex numbers.
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
name: CosmoLex
provenance_date: '2026-11-09'
provider_name: CosmoLex
provider_slug: cosmolex
slug: cosmolex-eligibility
source_date: '2026-11-09'
source_filename: cosmolex-eligibility.yml
source_heading: Eligibility
source_page: https://www.cosmolex.com/subscription-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CosmoLex\naid: cosmolex\nurl: https://www.cosmolex.com/subscription-agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: All usage prices are valid for the U.S. and Canada only. Please inquire about rates in other locations.\nentity_types: []\nrestricted_uses:\n- summary: No emergency services use\n  text: Using CosmoLex numbers to provide emergency services, such as 911-types of communication – Inbound and outbound\n    communications between emergency service providers and end users are explicitly not permitted on CosmoLex numbers.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cosmolex/eligibility/cosmolex-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from CosmoLex's own page on 2026-11-09.
synthetic: false
tags:
- Legal
- Law Practice Management
- Matter Management
- Billing
- Trust Accounting
- Time Tracking
- Legal Compliance
- Legal Software
---
