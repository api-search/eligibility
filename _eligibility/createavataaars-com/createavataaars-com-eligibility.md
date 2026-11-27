---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer, the mandatory protections of the country you live in still apply.
    type: individual
  - text: For business customers, the courts of Stuttgart decide.
    type: business
  minimum_age:
    text: You must be at least 16.
    value: '16'
  restricted_uses:
  - summary: Unlawful content, harassment or hate
    text: Do not use avatars for unlawful content, harassment or hate.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Beyond that, and to keep avatars in My avatars, you need a free Kurcz account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: createavataaars
provenance_date: '2026-11-09'
provider_name: createavataaars
provider_slug: createavataaars-com
slug: createavataaars-com-eligibility
source_date: '2026-11-09'
source_filename: createavataaars-com-eligibility.yml
source_heading: Eligibility
source_page: https://createavataaars.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: createavataaars\naid: createavataaars-com\nurl: https://createavataaars.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer, the mandatory protections of the country you live in still apply.\n- type: business\n  text: For business customers, the courts of Stuttgart decide.\nrestricted_uses:\n- summary: Unlawful content, harassment or hate\n  text: Do not use avatars for unlawful content, harassment or hate.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Beyond that, and to keep\
  \ avatars in My avatars, you need a free Kurcz account.\nminimum_age:\n  value: '16'\n  text: You must be at least 16.\n"
source_yaml_url: https://artifacts.apis.io/createavataaars-com/eligibility/createavataaars-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from createavataaars's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Avatars
- Avatar Generator
- Profile Pictures
- Illustration
- MCP
- AI Agents
---
