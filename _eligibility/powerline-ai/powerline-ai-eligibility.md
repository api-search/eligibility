---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if doing so is prohibited by law where you are.
  entity_types:
  - text: You must be at least 18 years old, or the age of majority where you live if that is higher, to use the Services.
    type: individual
  - text: If you use the Services on behalf of a company or other organisation, you represent that you have authority to bind it
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live if that is higher
    value: '18'
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: No account is required today. Access is anonymous and rate limits are applied per network address
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: powerline-ai
provenance_date: '2026-11-10'
provider_name: powerline-ai
provider_slug: powerline-ai
slug: powerline-ai-eligibility
source_date: '2026-11-10'
source_filename: powerline-ai-eligibility.yml
source_heading: Eligibility
source_page: https://powerline.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: powerline-ai\naid: powerline-ai\nurl: https://powerline.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if doing so is prohibited by law where you are.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher, to use the Services.\n- type: business\n  text: If you use the Services on behalf of a company or other organisation, you represent that you have authority\n    to bind it\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n\
  \  text: No account is required today. Access is anonymous and rate limits are applied per network address\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher\n"
source_yaml_url: https://artifacts.apis.io/powerline-ai/eligibility/powerline-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from powerline-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Email
- Productivity
---
