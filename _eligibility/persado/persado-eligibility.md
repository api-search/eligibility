---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF CUSTOMER, THEN YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: ARE OF LEGAL AGE TO FORM A BINDING CONTRACT
    value: null
  restricted_uses:
  - summary: Violating third-party privacy rights
    text: use the Services to transmit material in violation of any third party privacy rights or applicable privacy Laws
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
name: Persado
provenance_date: '2026-11-10'
provider_name: Persado
provider_slug: persado
slug: persado-eligibility
source_date: '2026-11-10'
source_filename: persado-eligibility.yml
source_heading: Eligibility
source_page: https://www.persado.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Persado\naid: persado\nurl: https://www.persado.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF CUSTOMER, THEN YOU REPRESENT THAT YOU HAVE THE AUTHORITY\n    TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Violating third-party privacy rights\n  text: use the Services to transmit material in violation of any third party privacy rights or applicable privacy\n    Laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: ARE OF LEGAL AGE TO FORM A BINDING CONTRACT\n"
source_yaml_url: https://artifacts.apis.io/persado/eligibility/persado-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Persado's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Apps
- Artificial Intelligence
- Generative AI
- Marketing
- Customer Engagement
- Content Generation
- Personalization
- Agents
- MCP
- Compliance
- Financial Services
---
