---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer or its Affiliates may purchase Services subject to the terms of this Agreement by executing Order Forms hereunder.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited illegal and harmful activities
    text: Any illegal activities, including advertising, transmitting, or otherwise making available gambling sites or services
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
name: Keatext
provenance_date: '2026-11-09'
provider_name: Keatext
provider_slug: keatext
slug: keatext-eligibility
source_date: '2026-11-09'
source_filename: keatext-eligibility.yml
source_heading: Eligibility
source_page: https://www.keatext.ai/en/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Keatext\naid: keatext\nurl: https://www.keatext.ai/en/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer or its Affiliates may purchase Services subject to the terms of this Agreement by executing Order\n    Forms hereunder.\nrestricted_uses:\n- summary: Prohibited illegal and harmful activities\n  text: Any illegal activities, including advertising, transmitting, or otherwise making available gambling sites\n    or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/keatext/eligibility/keatext-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Keatext's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Text Analytics
- Customer Experience
- Customer Feedback
- Sentiment Analysis
- Artificial Intelligence
- Natural Language Processing
- Voice of Customer
- Software-as-a-Service
---
