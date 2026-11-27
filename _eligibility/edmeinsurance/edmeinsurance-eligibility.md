---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: www.edmeinsurance.com offers the membership services for your authentic, bona fide, valid, legitimate and personal use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful, dishonest or improper use
    text: You declare that you will not use www.edmeinsurance.com services for any purpose that is unlawful, dishonest, unauthorized, improper and/or in contradiction of the terms, conditions, and notices contained herein.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: www.edmeinsurance.com reserves the right to accept or reject your application without assigning any whatsoever reason whatsoever.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Edme Insurance Brokers
provenance_date: '2026-11-09'
provider_name: Edme Insurance Brokers
provider_slug: edmeinsurance
slug: edmeinsurance-eligibility
source_date: '2026-11-09'
source_filename: edmeinsurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.edmeinsurance.com/terms-of-usage
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Edme Insurance Brokers\naid: edmeinsurance\nurl: https://www.edmeinsurance.com/terms-of-usage\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: www.edmeinsurance.com offers the membership services for your authentic, bona fide, valid, legitimate and\n    personal use only.\nrestricted_uses:\n- summary: Unlawful, dishonest or improper use\n  text: You declare that you will not use www.edmeinsurance.com services for any purpose that is unlawful, dishonest,\n    unauthorized, improper and/or in contradiction of the terms, conditions, and\
  \ notices contained herein.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: www.edmeinsurance.com reserves the right to accept or reject your application without assigning any whatsoever\n    reason whatsoever.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/edmeinsurance/eligibility/edmeinsurance-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Edme Insurance Brokers's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurance Brokerage
- Reinsurance
- Risk Management
- Employee Benefits
- Corporate Insurance
- India
---
