---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our SMS service is compatible with all major U.S. wireless carriers including but not limited to AT&T, Verizon, T-Mobile, Sprint, U.S. Cellular, and their affiliated carriers.
  entity_types:
  - text: SMS and voice messaging service operated by Robby on behalf of HVAC, plumbing, and home service contractors that use Robby.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No marketing or promotional use
    text: Messages are strictly operational and are not used for marketing or promotional purposes.
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
name: Robby
provenance_date: '2026-11-10'
provider_name: Robby
provider_slug: robby
slug: robby-eligibility
source_date: '2026-11-10'
source_filename: robby-eligibility.yml
source_heading: Eligibility
source_page: https://www.tryrobby.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Robby\naid: robby\nurl: https://www.tryrobby.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our SMS service is compatible with all major U.S. wireless carriers including but not limited to AT&T, Verizon,\n    T-Mobile, Sprint, U.S. Cellular, and their affiliated carriers.\nentity_types:\n- type: business\n  text: SMS and voice messaging service operated by Robby on behalf of HVAC, plumbing, and home service contractors\n    that use Robby.\nrestricted_uses:\n- summary: No marketing or promotional use\n  text: Messages are strictly operational and are not used for\
  \ marketing or promotional purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/robby/eligibility/robby-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Robby's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Home Services
- HVAC
- Field Service Management
- Artificial Intelligence
- Lead Generation
- Software-as-a-Service
- Y Combinator
---
