---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'By accessing or using the Product, You represent, warrant and signify that: (a) You are at least 18 years of age'
    type: individual
  - text: If You are agreeing to these Terms on behalf of any organization or company, You represent and warrant that You have the necessary authority to the bind the company and enter into these Terms.
    type: business
  minimum_age:
    text: You are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: 'You may not use our Website, services, or Products in any manner that: breaches any applicable local, national, or international law or regulation'
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
name: Chatter Research
provenance_date: '2026-11-09'
provider_name: Chatter Research
provider_slug: chatter-research
slug: chatter-research-eligibility
source_date: '2026-11-09'
source_filename: chatter-research-eligibility.yml
source_heading: Eligibility
source_page: https://www.chatterresearch.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chatter Research\naid: chatter-research\nurl: https://www.chatterresearch.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'By accessing or using the Product, You represent, warrant and signify that: (a) You are at least 18 years\n    of age'\n- type: business\n  text: If You are agreeing to these Terms on behalf of any organization or company, You represent and warrant that\n    You have the necessary authority to the bind the company and enter into these Terms.\nrestricted_uses:\n- summary: Unlawful or harmful use\n\
  \  text: 'You may not use our Website, services, or Products in any manner that: breaches any applicable local, national,\n    or international law or regulation'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/chatter-research/eligibility/chatter-research-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Chatter Research's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Feedback
- Customer Experience
- Surveys
- Voice of Customer
- Retail
- NPS
- Sentiment Analysis
---
