---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service only if you can form a binding contract with Inspiren and comply with all applicable laws.
    type: individual
  minimum_age:
    text: Any use of the Service by anyone under 18 years of age is strictly prohibited.
    value: '18'
  restricted_uses:
  - summary: Under-18 use prohibited
    text: Any use of the Service by anyone under 18 years of age is strictly prohibited.
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
name: Inspiren
provenance_date: '2026-11-09'
provider_name: Inspiren
provider_slug: inspiren
slug: inspiren-eligibility
source_date: '2026-11-09'
source_filename: inspiren-eligibility.yml
source_heading: Eligibility
source_page: https://www.inspiren.com/terms-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inspiren\naid: inspiren\nurl: https://www.inspiren.com/terms-privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a binding contract with Inspiren and comply with all applicable\n    laws.\nrestricted_uses:\n- summary: Under-18 use prohibited\n  text: Any use of the Service by anyone under 18 years of age is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use of the Service by anyone under\
  \ 18 years of age is strictly prohibited.\n"
source_yaml_url: https://artifacts.apis.io/inspiren/eligibility/inspiren-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Inspiren's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Senior Living
- Care
- Resident Safety
- Fall Prevention
- Remote Monitoring
- Artificial Intelligence
- IoT
- Health Tech
---
