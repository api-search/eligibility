---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for business use. You represent that you are entering into these Terms for business purposes and not as a consumer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical, legal, financial or emergency use
    text: the Services are not designed for medical, legal, financial, or emergency use
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
name: Quissly
provenance_date: '2026-11-10'
provider_name: Quissly
provider_slug: quissly-inc
slug: quissly-inc-eligibility
source_date: '2026-11-10'
source_filename: quissly-inc-eligibility.yml
source_heading: Eligibility
source_page: https://quissly.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quissly\naid: quissly-inc\nurl: https://quissly.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended for business use. You represent that you are entering into these Terms for business\n    purposes and not as a consumer.\nrestricted_uses:\n- summary: No medical, legal, financial or emergency use\n  text: the Services are not designed for medical, legal, financial, or emergency use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/quissly-inc/eligibility/quissly-inc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Quissly's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Search
- Artificial Intelligence
- Conversational Commerce
- Product Discovery
- Semantic Search
- Retail
---
