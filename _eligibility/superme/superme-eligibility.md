---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual’s employer
    type: individual
  - text: Organization
    type: business
  minimum_age:
    text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions) in any applicable jurisdiction (a “Minor”) is strictly prohibited
    value: '18'
  restricted_uses:
  - summary: Minors prohibited unless supervised by parent or guardian
    text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions) in any applicable jurisdiction (a “Minor”) is strictly prohibited
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
name: SuperMe
provenance_date: '2026-11-10'
provider_name: SuperMe
provider_slug: superme
slug: superme-eligibility
source_date: '2026-11-10'
source_filename: superme-eligibility.yml
source_heading: Eligibility
source_page: https://www.superme.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SuperMe\naid: superme\nurl: https://www.superme.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual’s\n    employer\n- type: business\n  text: Organization\nrestricted_uses:\n- summary: Minors prohibited unless supervised by parent or guardian\n  text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions)\n    in any applicable jurisdiction\
  \ (a “Minor”) is strictly prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: any access to, or use of, the Service by anyone who is a minor (which is under the age of 18 in most jurisdictions)\n    in any applicable jurisdiction (a “Minor”) is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/superme/eligibility/superme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SuperMe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Professional Network
- Expert Knowledge
- MCP
---
