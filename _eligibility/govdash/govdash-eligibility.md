---
claim_count: 1
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
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto
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
name: Govdash
provenance_date: '2026-11-09'
provider_name: Govdash
provider_slug: govdash
slug: govdash-eligibility
source_date: '2026-11-09'
source_filename: govdash-eligibility.yml
source_heading: Eligibility
source_page: https://www.govdash.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Govdash\naid: govdash\nurl: https://www.govdash.com/pages/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services,\n    Software or anything related thereto\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/govdash/eligibility/govdash-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Govdash's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government Contracting
- GovCon
- Artificial Intelligence
- Proposal Management
- Capture Management
- Public Sector
- Enterprise
---
