---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only a legally capable person who has reached the age of 18 or the age of majority in their jurisdiction (whichever is greater) may be the user.
    type: individual
  - text: If you access or use the Website or Platform on behalf of a company or other entity, then "you", the "user" and the "Client" comprise you as a person and that entity.
    type: business
  minimum_age:
    text: reached the age of 18 or the age of majority in their jurisdiction (whichever is greater)
    value: '18'
  restricted_uses:
  - summary: No monitoring or profiling of individuals
    text: to monitor, profile or collect information about individuals
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: we reserve the right to decline a registration or close an account at our discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AskWatch
provenance_date: '2026-11-09'
provider_name: AskWatch
provider_slug: askwatch-ai
slug: askwatch-ai-eligibility
source_date: '2026-11-09'
source_filename: askwatch-ai-eligibility.yml
source_heading: Eligibility
source_page: https://askwatch.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AskWatch\naid: askwatch-ai\nurl: https://askwatch.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only a legally capable person who has reached the age of 18 or the age of majority in their jurisdiction\n    (whichever is greater) may be the user.\n- type: business\n  text: If you access or use the Website or Platform on behalf of a company or other entity, then \"you\", the \"user\"\n    and the \"Client\" comprise you as a person and that entity.\nrestricted_uses:\n- summary: No monitoring or profiling of individuals\n \
  \ text: to monitor, profile or collect information about individuals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: we reserve the right to decline a registration or close an account at our discretion\nminimum_age:\n  value: '18'\n  text: reached the age of 18 or the age of majority in their jurisdiction (whichever is greater)\n"
source_yaml_url: https://artifacts.apis.io/askwatch-ai/eligibility/askwatch-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from AskWatch's own page on 2026-11-09.
synthetic: false
tags:
- AI Visibility
- Marketing
- Agencies
- Brand Monitoring
- AI engines
- Autopilot
---
