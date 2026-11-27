---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are made available for use in supporting Customer’s insurance brokerage or carrier business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Formal regulatory or legal use
    text: Use any Output in a regulatory submission, legal proceeding, complaint response, arbitration, or similar formal process without first having that Output independently verified by a qualified expert
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
name: General Magic
provenance_date: '2026-11-09'
provider_name: General Magic
provider_slug: general-magic
slug: general-magic-eligibility
source_date: '2026-11-09'
source_filename: general-magic-eligibility.yml
source_heading: Eligibility
source_page: https://generalmagic.inc/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: General Magic\naid: general-magic\nurl: https://generalmagic.inc/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are made available for use in supporting Customer’s insurance brokerage or carrier business\nrestricted_uses:\n- summary: Formal regulatory or legal use\n  text: Use any Output in a regulatory submission, legal proceeding, complaint response, arbitration, or similar\n    formal process without first having that Output independently verified by a qualified expert\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/general-magic/eligibility/general-magic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from General Magic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Insurance
- Brokerage
- Automation
---
