---
api_specs:
- filename: by-mason-openapi-generated.yml
  format: yaml
  label: By Mason API
  slug: by-mason-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/by-mason/openapi/_ae-authored/by-mason-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You may not remove or export from the United States or allow the export or re-export of the Services or anything related thereto
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
name: By Mason
provenance_date: '2026-11-09'
provider_name: By Mason
provider_slug: by-mason
slug: by-mason-eligibility
source_date: '2026-11-09'
source_filename: by-mason-eligibility.yml
source_heading: Eligibility
source_page: https://www.bymason.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: By Mason\naid: by-mason\nurl: https://www.bymason.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not remove or export from the United States or allow the export or re-export of the Services or\n    anything related thereto\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: you are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/by-mason/eligibility/by-mason-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from By Mason's own page on 2026-11-09.
synthetic: false
tags:
- IoT
- Device Management
- Enterprise Hardware
- Fleet Management
- Rugged Devices
- Healthcare
- Logistics
- Retail
---
