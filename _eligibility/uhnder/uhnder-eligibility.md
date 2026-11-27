---
claim_count: 2
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
  - summary: Life-saving or medical systems
    text: CUSTOMER UNDERSTANDS AND ACKNOWLEDGES THAT PRODUCTS AND SERVICES ARE NOT DESIGNED, MANUFACTURED OR TESTED FOR USE IN LIFE SAVING OR LIFE SUSTAINING SYSTEMS OR SUCH OTHER MEDICAL DEVICES.
  - summary: Export restrictions
    text: 'shall assure that the Products are not: (i) exported, directly or indirectly, in violation of Export Laws'
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
name: Uhnder
provenance_date: '2026-11-10'
provider_name: Uhnder
provider_slug: uhnder
slug: uhnder-eligibility
source_date: '2026-11-10'
source_filename: uhnder-eligibility.yml
source_heading: Eligibility
source_page: https://www.uhnder.com/site/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uhnder\naid: uhnder\nurl: https://www.uhnder.com/site/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Life-saving or medical systems\n  text: CUSTOMER UNDERSTANDS AND ACKNOWLEDGES THAT PRODUCTS AND SERVICES ARE NOT DESIGNED, MANUFACTURED OR TESTED\n    FOR USE IN LIFE SAVING OR LIFE SUSTAINING SYSTEMS OR SUCH OTHER MEDICAL DEVICES.\n- summary: Export restrictions\n  text: 'shall assure that the Products are not: (i) exported, directly or indirectly, in violation of Export Laws'\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uhnder/eligibility/uhnder-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Uhnder's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Semiconductors
- Automotive
- Radar
- ADAS
- Sensors
- Embedded
- Autonomous Vehicles
- Hardware
---
