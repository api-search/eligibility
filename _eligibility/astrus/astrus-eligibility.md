---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE AGREEING TO BE BOUND BY THIS AGREEMENT ON BEHALF OF YOUR EMPLOYER OR OTHER ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE FULL LEGAL AUTHORITY TO BIND YOUR EMPLOYER OR SUCH ENTITY TO THIS AGREEMENT.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Regulated or export-controlled data
    text: store or process regulated, export-controlled, or prohibited data types in violation of applicable law
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
name: Astrus
provenance_date: '2026-11-09'
provider_name: Astrus
provider_slug: astrus
slug: astrus-eligibility
source_date: '2026-11-09'
source_filename: astrus-eligibility.yml
source_heading: Eligibility
source_page: https://www.astrus.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astrus\naid: astrus\nurl: https://www.astrus.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE AGREEING TO BE BOUND BY THIS AGREEMENT ON BEHALF OF YOUR EMPLOYER OR OTHER ENTITY, YOU REPRESENT\n    AND WARRANT THAT YOU HAVE FULL LEGAL AUTHORITY TO BIND YOUR EMPLOYER OR SUCH ENTITY TO THIS AGREEMENT.\nrestricted_uses:\n- summary: Regulated or export-controlled data\n  text: store or process regulated, export-controlled, or prohibited data types in violation of applicable law\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/astrus/eligibility/astrus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Astrus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Semiconductors
- Chip Design
- Electronic Design Automation
- Analog Circuits
- Machine Learning
- Reinforcement Learning
---
