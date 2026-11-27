---
api_specs:
- filename: postman-collection
  format: yaml
  label: Opus Platform API
  slug: opus-platform-api
  spec_type: Postman
  url: https://developer.opus.com/api-reference/v0-jobs/postman-collection
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if it is an entity and not an individual, it is an entity duly formed, validly existing and in good standing under the laws of the jurisdiction in which it is established
    type: business
  minimum_age:
    text: you are at least 18 years old or the age of legal majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties and embargoed countries
    text: you are not located in and do not perform any Tasks in in a country that is subject to a U.S. government embargo
  - summary: Unlawful purposes
    text: use the Opus Platform for an unlawful purpose or otherwise in a manner inconsistent with any applicable laws or regulations.
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
name: AppliedAI (AAICO)
provenance_date: '2026-11-09'
provider_name: AppliedAI (AAICO)
provider_slug: aaico
slug: aaico-eligibility
source_date: '2026-11-09'
source_filename: aaico-eligibility.yml
source_heading: Eligibility
source_page: https://www.opus.com/legal-docs/Opus-Subscriber-Agreement.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppliedAI (AAICO)\naid: aaico\nurl: https://www.opus.com/legal-docs/Opus-Subscriber-Agreement.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if it is an entity and not an individual, it is an entity duly formed, validly existing and in good standing\n    under the laws of the jurisdiction in which it is established\nrestricted_uses:\n- summary: Sanctioned parties and embargoed countries\n  text: you are not located in and do not perform any Tasks in in a country that is subject to a U.S. government\n    embargo\n- summary: Unlawful\
  \ purposes\n  text: use the Opus Platform for an unlawful purpose or otherwise in a manner inconsistent with any applicable\n    laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old or the age of legal majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/aaico/eligibility/aaico-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AppliedAI (AAICO)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Workflow Automation
- Agents
- Enterprise
- Document Processing
- Regulated Industries
- Business Process Automation
- Banking
- Insurance
- Healthcare
- MCP
- A2A
---
