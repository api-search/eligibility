---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are provided solely for Your business purposes, subject to the terms and conditions of this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Cardholder data
    text: The Platform is not optimal for storing or processing cardholder information.
  - summary: Unlawful content or data
    text: use the Platform to store or transmit any content that infringes upon any person’s intellectual property rights, or is unlawful, racist, hateful, abusive, libelous, obscene, or discriminatory;
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
name: Kissflow
provenance_date: '2026-11-09'
provider_name: Kissflow
provider_slug: kissflow
slug: kissflow-eligibility
source_date: '2026-11-09'
source_filename: kissflow-eligibility.yml
source_heading: Eligibility
source_page: https://kissflow.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kissflow\naid: kissflow\nurl: https://kissflow.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are provided solely for Your business purposes, subject to the terms and conditions of this\n    Agreement.\nrestricted_uses:\n- summary: Cardholder data\n  text: The Platform is not optimal for storing or processing cardholder information.\n- summary: Unlawful content or data\n  text: use the Platform to store or transmit any content that infringes upon any person’s intellectual property\n    rights, or is\
  \ unlawful, racist, hateful, abusive, libelous, obscene, or discriminatory;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kissflow/eligibility/kissflow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Kissflow's own page on 2026-11-09.
synthetic: false
tags:
- Low-Code
- Workflow Automation
- enterprise-apps
- Integration
- Digital Transformation
- Company
---
