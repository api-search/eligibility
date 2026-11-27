---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Better Design on behalf of an organization, you represent that you have authority to bind that organization, and "you" refers to that organization.
    type: business
  minimum_age:
    text: You must be at least 13 years old (or 16 where local law sets a higher bar) to use Better Design.
    value: '13'
  restricted_uses:
  - summary: No harmful generated content
    text: Use the service to generate content that is hateful, harassing, deceptive, or otherwise prohibited by our policies.
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
name: Better Design
provenance_date: '2026-11-09'
provider_name: Better Design
provider_slug: better-design-com
slug: better-design-com-eligibility
source_date: '2026-11-09'
source_filename: better-design-com-eligibility.yml
source_heading: Eligibility
source_page: https://better-design.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Better Design\naid: better-design-com\nurl: https://better-design.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Better Design on behalf of an organization, you represent that you have authority to bind that\n    organization, and \"you\" refers to that organization.\nrestricted_uses:\n- summary: No harmful generated content\n  text: Use the service to generate content that is hateful, harassing, deceptive, or otherwise prohibited by our\n    policies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or 16 where local law sets a higher bar) to use Better Design.\n"
source_yaml_url: https://artifacts.apis.io/better-design-com/eligibility/better-design-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Better Design's own page on 2026-11-09.
synthetic: false
tags:
- Design
- Artificial Intelligence
- Components
- MCP
- UI
---
