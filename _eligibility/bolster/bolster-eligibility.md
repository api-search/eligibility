---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Members are independent contractors operating an independent business enterprise who use Bolster’s platform to offer and provide Services to Clients.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misuse of platform
    text: User acknowledges and agrees that Bolster has no responsibility for, control over, or involvement in the scope, nature, quality, character, timing, or location of any work or services performed by Member
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
name: Bolster
provenance_date: '2026-11-09'
provider_name: Bolster
provider_slug: bolster
slug: bolster-eligibility
source_date: '2026-11-09'
source_filename: bolster-eligibility.yml
source_heading: Eligibility
source_page: https://www.bolster.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bolster\naid: bolster\nurl: https://www.bolster.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Members are independent contractors operating an independent business enterprise who use Bolster’s platform\n    to offer and provide Services to Clients.\nrestricted_uses:\n- summary: Misuse of platform\n  text: User acknowledges and agrees that Bolster has no responsibility for, control over, or involvement in the\n    scope, nature, quality, character, timing, or location of any work or services performed by Member\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bolster/eligibility/bolster-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Bolster's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Executive Search
- Recruiting
- Talent Marketplace
- Fractional Executives
- Board Search
- Hiring
- Human Resources
---
