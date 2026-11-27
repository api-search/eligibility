---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Services on behalf of a company or other legal entity, you represent that you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control and sanctions
    text: To violate any applicable federal, state, local, or international law or regulation, including export control laws and regulations administered by the U.S. Bureau of Industry and Security (BIS) or the Office of Foreign Assets Control (OFAC);
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
name: Turing
provenance_date: '2026-11-10'
provider_name: Turing
provider_slug: turing-com
slug: turing-com-eligibility
source_date: '2026-11-10'
source_filename: turing-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.turing.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Turing\naid: turing-com\nurl: https://www.turing.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Services on behalf of a company or other legal entity, you represent that you have\n    authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Export control and sanctions\n  text: To violate any applicable federal, state, local, or international law or regulation, including export control\n    laws and regulations administered by the U.S. Bureau of Industry and Security (BIS)\
  \ or the Office of Foreign\n    Assets Control (OFAC);\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/turing-com/eligibility/turing-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Turing's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Training Data
- Reinforcement Learning
- Talent Network
- Enterprise AI
- Machine Learning
---
