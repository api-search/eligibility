---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using our Services or your account on behalf of a business, whether your own or your employer’s, the business agrees to be bound by our terms and policies.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Uses not designed for the Services
    text: This includes any use for which the Services were not designed, that may interfere with anyone else’s use of the Services
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
name: Ambyint
provenance_date: '2026-11-09'
provider_name: Ambyint
provider_slug: ambyint
slug: ambyint-eligibility
source_date: '2026-11-09'
source_filename: ambyint-eligibility.yml
source_heading: Eligibility
source_page: https://www.ambyint.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ambyint\naid: ambyint\nurl: https://www.ambyint.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using our Services or your account on behalf of a business, whether your own or your employer’s,\n    the business agrees to be bound by our terms and policies.\nrestricted_uses:\n- summary: Uses not designed for the Services\n  text: This includes any use for which the Services were not designed, that may interfere with anyone else’s use\n    of the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ambyint/eligibility/ambyint-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Ambyint's own page on 2026-11-09.
synthetic: false
tags:
- Production Optimization
- Artificial Lift
- Oil and Gas
- Artificial Intelligence
- Autonomous Setpoint Management
- Anomaly Detection
- Analytics
---
