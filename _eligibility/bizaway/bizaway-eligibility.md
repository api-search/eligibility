---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-business use
    text: In the event that, by agreement with the Customer, the Platform is used by users for non-business purposes, or via their own private billing profile, BizAway will act as the Data Controller.
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
name: BizAway
provenance_date: '2026-11-09'
provider_name: BizAway
provider_slug: bizaway
slug: bizaway-eligibility
source_date: '2026-11-09'
source_filename: bizaway-eligibility.yml
source_heading: Eligibility
source_page: https://www.bizaway.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BizAway\naid: bizaway\nurl: https://www.bizaway.com/en/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-business use\n  text: In the event that, by agreement with the Customer, the Platform is used by users for non-business purposes,\n    or via their own private billing profile, BizAway will act as the Data Controller.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bizaway/eligibility/bizaway-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from BizAway's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Software-as-a-Service
- B2B
- Platform
---
