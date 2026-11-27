---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you're using Étincel on behalf of an organization, you're confirming you have the authority to bind that organization to these terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, defamatory or infringing content
    text: Don't use Étincel to generate content that's illegal, defamatory, or infringing.
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
name: Étincel
provenance_date: '2026-11-09'
provider_name: Étincel
provider_slug: etincel-ai
slug: etincel-ai-eligibility
source_date: '2026-11-09'
source_filename: etincel-ai-eligibility.yml
source_heading: Eligibility
source_page: https://etincel.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Étincel\naid: etincel-ai\nurl: https://etincel.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you're using Étincel on behalf of an organization, you're confirming you have the authority to bind that\n    organization to these terms.\nrestricted_uses:\n- summary: Illegal, defamatory or infringing content\n  text: Don't use Étincel to generate content that's illegal, defamatory, or infringing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/etincel-ai/eligibility/etincel-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Étincel's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Writing
- Voice
- Claude
---
