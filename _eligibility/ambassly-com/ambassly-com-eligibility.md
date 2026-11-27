---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using Ambassly, you confirm you can form a binding contract on behalf of yourself or the company you represent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud and unlawful tracking
    text: Do not use Ambassly to facilitate fraud, to track individuals unlawfully, to violate Stripe’s terms, or to attempt to reverse-engineer or interfere with the service’s normal operation.
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
name: Ambassly
provenance_date: '2026-11-09'
provider_name: Ambassly
provider_slug: ambassly-com
slug: ambassly-com-eligibility
source_date: '2026-11-09'
source_filename: ambassly-com-eligibility.yml
source_heading: Eligibility
source_page: https://ambassly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ambassly\naid: ambassly-com\nurl: https://ambassly.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accessing or using Ambassly, you confirm you can form a binding contract on behalf of yourself or the\n    company you represent\nrestricted_uses:\n- summary: Fraud and unlawful tracking\n  text: Do not use Ambassly to facilitate fraud, to track individuals unlawfully, to violate Stripe’s terms, or\n    to attempt to reverse-engineer or interfere with the service’s normal operation.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ambassly-com/eligibility/ambassly-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Ambassly's own page on 2026-11-09.
synthetic: false
tags:
- Affiliates
- Software-as-a-Service
- Marketing
- Software
- Platform
---
