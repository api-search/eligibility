---
api_specs:
- filename: clonekit-ai-openapi-generated.yml
  format: yaml
  label: CloneKit REST API
  slug: clonekit-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clonekit-ai/openapi/_ae-authored/clonekit-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18, or the age of majority where you live, to use CloneKit.
    type: individual
  - text: If you use CloneKit for a company, you confirm that you may bind that company to these terms.
    type: business
  minimum_age:
    text: You must be at least 18, or the age of majority where you live, to use CloneKit.
    value: '18'
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
name: CloneKit
provenance_date: '2026-11-09'
provider_name: CloneKit
provider_slug: clonekit-ai
slug: clonekit-ai-eligibility
source_date: '2026-11-09'
source_filename: clonekit-ai-eligibility.yml
source_heading: Eligibility
source_page: https://clonekit.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CloneKit\naid: clonekit-ai\nurl: https://clonekit.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live, to use CloneKit.\n- type: business\n  text: If you use CloneKit for a company, you confirm that you may bind that company to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live, to use CloneKit.\n"
source_yaml_url: https://artifacts.apis.io/clonekit-ai/eligibility/clonekit-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from CloneKit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Model Context Protocol
- Marketplace
- Playbooks
- Automation
---
