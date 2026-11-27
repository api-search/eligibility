---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not order or obtain products or services from SenseGlove if you (a) Do not agree to these Terms, (B) are not older then (I) at least 18 years old (II) legal age to form a binding contract with SenseGlove.
    type: individual
  minimum_age:
    text: at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Not a consumer product
    text: However the SenseGlove is not intended as a consumer product.
  - summary: Certification responsibility
    text: if implemented of resold within a product the Customer is responsible for all applicable certifications such as FDA and CE certifications.
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
name: Adjuvo Motion
provenance_date: '2026-11-09'
provider_name: Adjuvo Motion
provider_slug: adjuvomotion
slug: adjuvomotion-eligibility
source_date: '2026-11-09'
source_filename: adjuvomotion-eligibility.yml
source_heading: Eligibility
source_page: https://senseglove.com/terms-of-sale/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adjuvo Motion\naid: adjuvomotion\nurl: https://senseglove.com/terms-of-sale/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not order or obtain products or services from SenseGlove if you (a) Do not agree to these Terms,\n    (B) are not older then (I) at least 18 years old (II) legal age to form a binding contract with SenseGlove.\nrestricted_uses:\n- summary: Not a consumer product\n  text: However the SenseGlove is not intended as a consumer product.\n- summary: Certification responsibility\n  text: if implemented of resold\
  \ within a product the Customer is responsible for all applicable certifications\n    such as FDA and CE certifications.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/adjuvomotion/eligibility/adjuvomotion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Adjuvo Motion's own page on 2026-11-09.
synthetic: false
tags:
- Haptics
- Virtual Reality
- Extended Reality
- Robotics
- Hardware
- SDK
- Simulation
- Training
- Teleoperation
- Wearables
---
