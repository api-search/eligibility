---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you (either an individual or an entity, referred to herein as “ Customer ,”
    type: individual
  - text: Your employees, representatives, agents, Affiliates, and contractors who are authorized by you to access / use the Services on your behalf
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or harmful use
    text: Use the Services to violate applicable law, infringe upon the rights of others, distribute defamatory or harmful content, or transmit viruses or harmful code;
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
name: Clootrack
provenance_date: '2026-11-09'
provider_name: Clootrack
provider_slug: clootrack-com
slug: clootrack-com-eligibility
source_date: '2026-11-09'
source_filename: clootrack-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.clootrack.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clootrack\naid: clootrack-com\nurl: https://www.clootrack.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you (either an individual or an entity, referred to herein as “ Customer ,”\n- type: business\n  text: Your employees, representatives, agents, Affiliates, and contractors who are authorized by you to access\n    / use the Services on your behalf\nrestricted_uses:\n- summary: No unlawful or harmful use\n  text: Use the Services to violate applicable law, infringe upon the rights of others, distribute defamatory\
  \ or\n    harmful content, or transmit viruses or harmful code;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clootrack-com/eligibility/clootrack-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Clootrack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Experience
- Voice of the Customer
- Customer Feedback Analytics
- Artificial Intelligence
- Sentiment Analysis
- Model Context Protocol
---
