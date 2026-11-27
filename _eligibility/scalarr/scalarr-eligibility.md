---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent to us that you are lawfully able to enter into contracts.
    type: individual
  - text: If you are entering into these contracts for an entity, such as the company you work for, you represent to us that you have legal authority to bind that entity.
    type: business
  - source: https://edgelabs.ai/terms-and-conditions
    text: If you are entering into this Agreement for an entity, such as the company you work for, you represent to us that you have legal authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - source: https://edgelabs.ai/terms-and-conditions
    summary: No third-party service provision without consent
    text: use it for providing services to a third party, or grant any rights in and to EdgeLabs Software or documentation to a third party in any form
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
name: Scalarr
provenance_date: '2026-11-10'
provider_name: Scalarr
provider_slug: scalarr
slug: scalarr-eligibility
source_date: '2026-11-10'
source_filename: scalarr-eligibility.yml
source_heading: Eligibility
source_page: https://scalarr.io/document/services_agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scalarr\naid: scalarr\nurl: https://scalarr.io/document/services_agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://edgelabs.ai/terms-and-conditions\n  - https://scalarr.io/document/services_agreement/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent to us that you are lawfully able to enter into contracts.\n- type: business\n  text: If you are entering into these contracts for an entity, such as the company you work for, you represent\n    to us that you have legal authority to bind that entity.\n- type: business\n  text: If you are\
  \ entering into this Agreement for an entity, such as the company you work for, you represent to\n    us that you have legal authority to bind that entity.\n  source: https://edgelabs.ai/terms-and-conditions\nrestricted_uses:\n- summary: No third-party service provision without consent\n  text: use it for providing services to a third party, or grant any rights in and to EdgeLabs Software or documentation\n    to a third party in any form\n  source: https://edgelabs.ai/terms-and-conditions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/scalarr/eligibility/scalarr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Scalarr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Runtime Security
- AI Agent Security
- Container Security
- Kubernetes
- Edge Computing
- Vulnerability Management
- Compliance
- NIS2
- Machine Learning
- Artificial Intelligence
- Open Source
- Fraud Prevention
- Mobile Ad Fraud
---
