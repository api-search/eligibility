---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you open an account on behalf of a company, organization, or other entity, then (a) "you" includes you and that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited advertising and conduct
    text: (iii) to advertise or promote adult services, illegal gambling, counterfeit or pirated goods or services, or violate any securities or commodities regulations
  - summary: Defrauding or harassment
    text: (iv) to defraud, deceive or mislead anyone; (v) to communicate or transmit content that is defamatory, dishonest, obscene, sexually explicit, pornographic, vulgar or offensive
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You grant permission to Sesame Labs to check your credit history and rating, and to refuse you service or suspend your account at any time based on our evaluation of your creditworthiness.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sesame Labs
provenance_date: '2026-11-10'
provider_name: Sesame Labs
provider_slug: sesame-labs
slug: sesame-labs-eligibility
source_date: '2026-11-10'
source_filename: sesame-labs-eligibility.yml
source_heading: Eligibility
source_page: https://www.usenotch.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sesame Labs\naid: sesame-labs\nurl: https://www.usenotch.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you open an account on behalf of a company, organization, or other entity, then (a) \"you\" includes you\n    and that entity\nrestricted_uses:\n- summary: Prohibited advertising and conduct\n  text: (iii) to advertise or promote adult services, illegal gambling, counterfeit or pirated goods or services,\n    or violate any securities or commodities regulations\n- summary: Defrauding or harassment\n  text: (iv)\
  \ to defraud, deceive or mislead anyone; (v) to communicate or transmit content that is defamatory, dishonest,\n    obscene, sexually explicit, pornographic, vulgar or offensive\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You grant permission to Sesame Labs to check your credit history and rating, and to refuse you service or\n    suspend your account at any time based on our evaluation of your creditworthiness.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sesame-labs/eligibility/sesame-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Sesame Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Advertising
- Video
- Marketing
- Generative AI
- MCP
- Agents
---
