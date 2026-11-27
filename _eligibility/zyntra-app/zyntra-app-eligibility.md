---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept them for a company, you confirm that you can bind it.
    type: business
  - text: If you are a consumer in the European Union and want a paid plan to start straight away
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use limits
    text: 'Do not use the Service to: register accounts in bulk on services you do not own or are not authorized to test; get around another service''s sign-up or verification checks'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The address you use must be yours and current.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zyntra
provenance_date: '2026-11-10'
provider_name: Zyntra
provider_slug: zyntra-app
slug: zyntra-app-eligibility
source_date: '2026-11-10'
source_filename: zyntra-app-eligibility.yml
source_heading: Eligibility
source_page: https://zyntra.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zyntra\naid: zyntra-app\nurl: https://zyntra.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept them for a company, you confirm that you can bind it.\n- type: individual\n  text: If you are a consumer in the European Union and want a paid plan to start straight away\nrestricted_uses:\n- summary: Acceptable use limits\n  text: 'Do not use the Service to: register accounts in bulk on services you do not own or are not authorized to\n    test; get around another service''s sign-up or verification checks'\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: The address you use must be yours and current.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zyntra-app/eligibility/zyntra-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Zyntra's own page on 2026-11-10.
synthetic: false
tags:
- Email Testing
- Automated Tests
- QA
- Password Reset
- Magic Link
---
