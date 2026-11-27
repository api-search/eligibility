---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By signing this agreement, the Client ("Franchisee") hereby acknowledges and agrees to integrate Delightree, as described in the Scope of Services, into its franchise operations as a mandatory component for all new and existing locations.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations of the United States Department of Commerce
  - summary: U.S. Government use
    text: any use modification, reproduction, release, performance, display, or disclosure of such commercial software or commercial software documentation by the U.S. Government will be governed solely by the terms of this Agreement and will be prohibited except to the extent expressly permitted by the terms of this Agreement.
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
name: Delightree
provenance_date: '2026-11-09'
provider_name: Delightree
provider_slug: delightree
slug: delightree-eligibility
source_date: '2026-11-09'
source_filename: delightree-eligibility.yml
source_heading: Eligibility
source_page: https://www.delightree.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delightree\naid: delightree\nurl: https://www.delightree.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By signing this agreement, the Client (\"Franchisee\") hereby acknowledges and agrees to integrate Delightree,\n    as described in the Scope of Services, into its franchise operations as a mandatory component for all new and\n    existing locations.\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services,\n    Software\
  \ or anything related thereto, or any direct product thereof in violation of any restrictions, laws or\n    regulations of the United States Department of Commerce\n- summary: U.S. Government use\n  text: any use modification, reproduction, release, performance, display, or disclosure of such commercial software\n    or commercial software documentation by the U.S. Government will be governed solely by the terms of this Agreement\n    and will be prohibited except to the extent expressly permitted by the terms of this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/delightree/eligibility/delightree-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Delightree's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Productivity
- Franchise Management
- Task Management
- Training
- Knowledge Base
- Software-as-a-Service
---
