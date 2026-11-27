---
api_specs:
- filename: casemagic-ai-cases-api-openapi.yml
  format: yaml
  label: CaseMagic Cases API
  slug: casemagic-ai-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casemagic-ai/openapi/casemagic-ai-cases-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harassment and unlawful use
    text: Do not use CaseMagic to harass anyone, and do not use case data to do anything unlawful.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The 7 -day trial requires a card and converts to a paid subscription unless cancelled before it ends.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CaseMagic
provenance_date: '2026-11-09'
provider_name: CaseMagic
provider_slug: casemagic-ai
slug: casemagic-ai-eligibility
source_date: '2026-11-09'
source_filename: casemagic-ai-eligibility.yml
source_heading: Eligibility
source_page: https://casemagic.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CaseMagic\naid: casemagic-ai\nurl: https://casemagic.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment and unlawful use\n  text: Do not use CaseMagic to harass anyone, and do not use case data to do anything unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The 7 -day trial requires a card and converts to a paid subscription unless cancelled before it ends.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/casemagic-ai/eligibility/casemagic-ai-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from CaseMagic's own page on 2026-11-09.
synthetic: false
tags:
- Legal Tech
- Court Data
- Alerts
- Free
---
