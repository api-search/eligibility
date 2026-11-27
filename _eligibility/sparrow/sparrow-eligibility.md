---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to the terms of this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Service or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations of the United States Department of Commerce
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
name: Sparrow
provenance_date: '2026-11-10'
provider_name: Sparrow
provider_slug: sparrow
slug: sparrow-eligibility
source_date: '2026-11-10'
source_filename: sparrow-eligibility.yml
source_heading: Eligibility
source_page: https://sparrow.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sparrow\naid: sparrow\nurl: https://sparrow.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By entering into this Agreement on behalf of a company or other legal entity, you represent that you have\n    the authority to bind such entity to the terms of this Agreement.\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Service\n    or anything related thereto, or any direct product thereof in violation of any restrictions,\
  \ laws or regulations\n    of the United States Department of Commerce\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sparrow/eligibility/sparrow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Sparrow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Leave Management
- Human Resources
- Payroll
- Compliance
- Employee Benefits
- Absence Management
- Software-as-a-Service
---
