---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Services or to apply to the Anthology Fellows community.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Services or to apply to the Anthology Fellows community.
    value: '18'
  restricted_uses:
  - summary: No AI tools during interviews
    text: Use a large language model or other AI tool to generate, draft, or dictate your answers
  - summary: No impersonation or misrepresented identity
    text: Impersonate any person or misrepresent your identity, credentials, experience, or affiliation
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
name: Polymath
provenance_date: '2026-11-10'
provider_name: Polymath
provider_slug: polymathlabs-ai
slug: polymathlabs-ai-eligibility
source_date: '2026-11-10'
source_filename: polymathlabs-ai-eligibility.yml
source_heading: Eligibility
source_page: https://polymathlabs.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Polymath\naid: polymathlabs-ai\nurl: https://polymathlabs.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services or to apply to the Anthology Fellows community.\nrestricted_uses:\n- summary: No AI tools during interviews\n  text: Use a large language model or other AI tool to generate, draft, or dictate your answers\n- summary: No impersonation or misrepresented identity\n  text: Impersonate any person or misrepresent your identity, credentials, experience, or affiliation\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services or to apply to the Anthology Fellows community.\n"
source_yaml_url: https://artifacts.apis.io/polymathlabs-ai/eligibility/polymathlabs-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Polymath's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Simulation
- Autonomous Agents
---
