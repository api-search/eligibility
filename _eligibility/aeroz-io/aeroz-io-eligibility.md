---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are offered for business and professional use only and are not intended for consumers acting for personal, family, or household purposes
    type: business
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction and capable of forming a binding contract.
    value: age of majority
  restricted_uses:
  - summary: Export controls and sanctions
    text: use the Services in violation of applicable law, export controls, or sanctions.
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
name: Aeroz
provenance_date: '2026-11-09'
provider_name: Aeroz
provider_slug: aeroz-io
slug: aeroz-io-eligibility
source_date: '2026-11-09'
source_filename: aeroz-io-eligibility.yml
source_heading: Eligibility
source_page: https://aeroz.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aeroz\naid: aeroz-io\nurl: https://aeroz.io/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are offered for business and professional use only and are not intended for consumers acting\n    for personal, family, or household purposes\nrestricted_uses:\n- summary: Export controls and sanctions\n  text: use the Services in violation of applicable law, export controls, or sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must\
  \ be at least the age of majority in your jurisdiction and capable of forming a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/aeroz-io/eligibility/aeroz-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aeroz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Supply Chain
- Traceability
- Authentication
- Compliance
- NFC
---
