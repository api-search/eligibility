---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Company Service, or any direct product thereof in violation of any restrictions, laws or regulations of the United States Department of Commerce
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
name: Copley
provenance_date: '2026-11-09'
provider_name: Copley
provider_slug: copley
slug: copley-eligibility
source_date: '2026-11-09'
source_filename: copley-eligibility.yml
source_heading: Eligibility
source_page: https://docs.copley.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Copley\naid: copley\nurl: https://docs.copley.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Company\n    Service, or any direct product thereof in violation of any restrictions, laws or regulations of the United\
  \ States\n    Department of Commerce\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/copley/eligibility/copley-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Copley's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- Demand Engineering
- Platform
- Software-as-a-Service
- Company
---
