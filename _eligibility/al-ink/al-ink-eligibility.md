---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you must be at least 18 years old with full legal capacity.
    type: individual
  minimum_age:
    text: you must be at least 18 years old with full legal capacity.
    value: '18'
  restricted_uses:
  - summary: Acceptable use red lines
    text: 'you must not: harass, threaten, defraud, impersonate others, or submit unlawful content'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: claiming a protected name requires identity verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: alink
provenance_date: '2026-11-09'
provider_name: alink
provider_slug: al-ink
slug: al-ink-eligibility
source_date: '2026-11-09'
source_filename: al-ink-eligibility.yml
source_heading: Eligibility
source_page: https://al.ink/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: alink\naid: al-ink\nurl: https://al.ink/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you must be at least 18 years old with full legal capacity.\nrestricted_uses:\n- summary: Acceptable use red lines\n  text: 'you must not: harass, threaten, defraud, impersonate others, or submit unlawful content'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: claiming a protected name requires identity verification.\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old with full legal capacity.\n"
source_yaml_url: https://artifacts.apis.io/al-ink/eligibility/al-ink-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from alink's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Public-Page
- Link-Service
---
