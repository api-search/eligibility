---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least the age of majority in your jurisdiction of residence (and in all events at least 18 years of age) to access or use the Websites or create an account.
    type: individual
  minimum_age:
    text: at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or objectionable content
    text: Content that is unlawful, libelous, defamatory, obscene, pornographic, indecent, lewd, suggestive, harassing, threatening
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
name: Luminos.AI
provenance_date: '2026-11-10'
provider_name: Luminos.AI
provider_slug: luminosai
slug: luminosai-eligibility
source_date: '2026-11-10'
source_filename: luminosai-eligibility.yml
source_heading: Eligibility
source_page: https://www.luminos.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Luminos.AI\naid: luminosai\nurl: https://www.luminos.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your jurisdiction of residence (and in all events at least 18\n    years of age) to access or use the Websites or create an account.\nrestricted_uses:\n- summary: Unlawful or objectionable content\n  text: Content that is unlawful, libelous, defamatory, obscene, pornographic, indecent, lewd, suggestive, harassing,\n    threatening\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/luminosai/eligibility/luminosai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Luminos.AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Governance
- AI Evaluation
- Compliance
- Risk Management
- AI Safety
- RegTech
- AI Agents
---
