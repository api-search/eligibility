---
api_specs:
- filename: openapi.json
  format: json
  label: Angels for Agents Discovery API
  slug: angels-for-agents-discovery-api
  spec_type: OpenAPI
  url: https://angelsforagents.com/openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Sanctions and geographic eligibility must be confirmed before transfer.
  entity_types:
  - text: Every applicant must identify a real human controller or authorized legal entity.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Permitted uses defined in milestone contract
    text: milestone contract defining baseline, measurable outcomes, deadline, permitted uses, evidence sources, stop conditions
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Any grant, investment, loan, or other transaction requires separate verification, diligence, definitive written terms, and acceptance by authorized persons.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Angels for Agents
provenance_date: '2026-11-09'
provider_name: Angels for Agents
provider_slug: angelsforagents-com
slug: angelsforagents-com-eligibility
source_date: '2026-11-09'
source_filename: angelsforagents-com-eligibility.yml
source_heading: Eligibility
source_page: https://angelsforagents.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Angels for Agents\naid: angelsforagents-com\nurl: https://angelsforagents.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Sanctions and geographic eligibility must be confirmed before transfer.\nentity_types:\n- type: individual\n  text: Every applicant must identify a real human controller or authorized legal entity.\nrestricted_uses:\n- summary: Permitted uses defined in milestone contract\n  text: milestone contract defining baseline, measurable outcomes, deadline, permitted uses, evidence sources, stop\n    conditions\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: Any grant, investment, loan, or other transaction requires separate verification, diligence, definitive\n    written terms, and acceptance by authorized persons.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/angelsforagents-com/eligibility/angelsforagents-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Angels for Agents's own page on 2026-11-09.
synthetic: false
tags:
- Capital
- Artificial Intelligence
- Agents
- Venture Funding
- Networks
---
