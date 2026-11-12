---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Enterprise customers may execute a negotiated DPA.
    type: business
  minimum_age:
    text: You must be at least 18 and provide accurate registration information.
    value: '18'
  restricted_uses:
  - summary: Impersonation
    text: impersonate any person or entity, or misrepresent your affiliation
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
name: Clueso
provenance_date: '2026-11-09'
provider_name: Clueso
provider_slug: clueso-io
slug: clueso-io-eligibility
source_date: '2026-11-09'
source_filename: clueso-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.clueso.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clueso\naid: clueso-io\nurl: https://www.clueso.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Enterprise customers may execute a negotiated DPA.\nrestricted_uses:\n- summary: Impersonation\n  text: impersonate any person or entity, or misrepresent your affiliation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and provide accurate registration information.\n"
source_yaml_url: https://artifacts.apis.io/clueso-io/eligibility/clueso-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Clueso's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Video
- Documentation
- Screen Recording
- Video Creation
- Knowledge Base
- Training
- MCP
---
