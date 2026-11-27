---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customers outside of the EU shall be responsible for obtaining customs' clearance for the Goods.
  entity_types:
  - text: The Order constitutes an offer by the Customer to purchase Goods, Software and/or Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls and sanctions
    text: The Customer will comply with all laws and rules relating to its use of the Goods and Software, including the US Export Administration Regulations and any other relevant prohibitions or sanctions (Export Controls).
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
name: Ultraleap
provenance_date: '2026-11-10'
provider_name: Ultraleap
provider_slug: ultraleap
slug: ultraleap-eligibility
source_date: '2026-11-10'
source_filename: ultraleap-eligibility.yml
source_heading: Eligibility
source_page: https://www.ultraleap.com/legal/ultraleap-ltd-terms-conditions-of-business/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ultraleap\naid: ultraleap\nurl: https://www.ultraleap.com/legal/ultraleap-ltd-terms-conditions-of-business/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customers outside of the EU shall be responsible for obtaining customs' clearance for the Goods.\nentity_types:\n- type: business\n  text: The Order constitutes an offer by the Customer to purchase Goods, Software and/or Services\nrestricted_uses:\n- summary: Export controls and sanctions\n  text: The Customer will comply with all laws and rules relating to its use of the Goods and Software, including\n    the US Export Administration\
  \ Regulations and any other relevant prohibitions or sanctions (Export Controls).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ultraleap/eligibility/ultraleap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Ultraleap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hand Tracking
- Computer Vision
- Spatial Computing
- Haptics
- Augmented Reality
- Virtual Reality
- Extended Reality
- Gesture Recognition
- OpenXR
- SDK
- Hardware
- Human-Computer Interaction
---
