---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Application or the company, or other legal entity on behalf of which such individual is accessing or using the Application, as applicable.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: NSFW content
    text: The use of the Application to generate, create, or produce any Not Safe For Work (NSFW) content, including but not limited to adult content, sexually explicit material, pornography, or any content of a sexual nature is strictly prohibited.
  - summary: Defamatory content
    text: The use of the Application to generate, create, or produce any content that is defamatory in nature, including but not limited to content that harms the reputation of individuals or entities, spreads false information, or contains libelous or slanderous material is strictly prohibited.
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
name: saifs-ai
provenance_date: '2026-11-10'
provider_name: saifs-ai
provider_slug: saifs-ai
slug: saifs-ai-eligibility
source_date: '2026-11-10'
source_filename: saifs-ai-eligibility.yml
source_heading: Eligibility
source_page: https://saifs.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: saifs-ai\naid: saifs-ai\nurl: https://saifs.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Application or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Application, as applicable.\nrestricted_uses:\n- summary: NSFW content\n  text: The use of the Application to generate, create, or produce any Not Safe For Work (NSFW) content, including\n    but not limited to adult content, sexually explicit material, pornography, or any\
  \ content of a sexual nature\n    is strictly prohibited.\n- summary: Defamatory content\n  text: The use of the Application to generate, create, or produce any content that is defamatory in nature, including\n    but not limited to content that harms the reputation of individuals or entities, spreads false information,\n    or contains libelous or slanderous material is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/saifs-ai/eligibility/saifs-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from saifs-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Content Creation
- Video Generation
- Image Generation
- Audio Generation
---
