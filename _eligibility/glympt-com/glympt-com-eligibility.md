---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act for an organisation, you confirm authority to bind it.
    type: business
  minimum_age:
    text: You must be at least 16; if local law requires an older contracting age, that age applies.
    value: '16'
  restricted_uses:
  - summary: Unauthorised access and security testing
    text: access private systems, bypass controls, test vulnerabilities without authorisation, or target private networks or metadata services
  - summary: Unlawful spam and privacy violations
    text: send unlawful spam, harass, discriminate unlawfully, or violate privacy, marketing, sanctions, export-control, or other laws
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
name: glympt-com
provenance_date: '2026-11-09'
provider_name: glympt-com
provider_slug: glympt-com
slug: glympt-com-eligibility
source_date: '2026-11-09'
source_filename: glympt-com-eligibility.yml
source_heading: Eligibility
source_page: https://glympt.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: glympt-com\naid: glympt-com\nurl: https://glympt.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act for an organisation, you confirm authority to bind it.\nrestricted_uses:\n- summary: Unauthorised access and security testing\n  text: access private systems, bypass controls, test vulnerabilities without authorisation, or target private networks\n    or metadata services\n- summary: Unlawful spam and privacy violations\n  text: send unlawful spam, harass, discriminate unlawfully, or violate privacy, marketing,\
  \ sanctions, export-control,\n    or other laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16; if local law requires an older contracting age, that age applies.\n"
source_yaml_url: https://artifacts.apis.io/glympt-com/eligibility/glympt-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from glympt-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Enrichment
- Technographics
- MCP
---
