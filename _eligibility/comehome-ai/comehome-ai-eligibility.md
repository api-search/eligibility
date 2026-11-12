---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform is available exclusively to users within the United States. Users outside the United States, and those protected by the General Data Protection Regulation (GDPR), are prohibited from using the Platform.
  entity_types:
  - text: The Platform is intended for users who are at least 18 years old. Minors under 18 may use the Platform only with the consent and under the supervision of a parent or legal guardian.
    type: individual
  minimum_age:
    text: The Platform is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Non-consumer use prohibited
    text: The Platform is authorized for individual, consumer use only. Any other use is considered unauthorized.
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
name: ComeHome.ai
provenance_date: '2026-11-09'
provider_name: ComeHome.ai
provider_slug: comehome-ai
slug: comehome-ai-eligibility
source_date: '2026-11-09'
source_filename: comehome-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.comehome.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ComeHome.ai\naid: comehome-ai\nurl: https://www.comehome.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform is available exclusively to users within the United States. Users outside the United States,\n    and those protected by the General Data Protection Regulation (GDPR), are prohibited from using the Platform.\nentity_types:\n- type: individual\n  text: The Platform is intended for users who are at least 18 years old. Minors under 18 may use the Platform only\n    with the consent and under the supervision of a parent or legal guardian.\nrestricted_uses:\n\
  - summary: Non-consumer use prohibited\n  text: The Platform is authorized for individual, consumer use only. Any other use is considered unauthorized.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Platform is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/comehome-ai/eligibility/comehome-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ComeHome.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Moving
- Moving Cost Estimates
- Virtual Survey
- Computer Vision
- Lead Scoring
- Artificial Intelligence
- MCP
---
