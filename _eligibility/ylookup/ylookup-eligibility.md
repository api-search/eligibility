---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of a company or other legal entity, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk uses
    text: The Services are not designed for high-risk environments or uses requiring fail-safe performance, including life support systems, operation of nuclear facilities, air traffic control, or the direct provision of regulated financial or investment advice without human review.
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
name: Ylookup
provenance_date: '2026-11-10'
provider_name: Ylookup
provider_slug: ylookup
slug: ylookup-eligibility
source_date: '2026-11-10'
source_filename: ylookup-eligibility.yml
source_heading: Eligibility
source_page: https://www.ylookup.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ylookup\naid: ylookup\nurl: https://www.ylookup.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a company or other legal entity, you represent that you have\n    authority to bind that entity\nrestricted_uses:\n- summary: High-risk uses\n  text: The Services are not designed for high-risk environments or uses requiring fail-safe performance, including\n    life support systems, operation of nuclear facilities, air traffic control, or the direct provision of regulated\n  \
  \  financial or investment advice without human review.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ylookup/eligibility/ylookup-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Ylookup's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Artificial Intelligence
- AI Agents
- Fund Administration
- Corporate Services
- Financial Services
- Workflow Automation
- Tax and Audit
---
