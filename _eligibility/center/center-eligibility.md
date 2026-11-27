---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter a binding contract.
    type: individual
  - text: If you use Center for a business, you agree on behalf of that business and confirm you have authority to do so.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter a binding contract.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: Center is not an emergency service and must not be relied on in an emergency.
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
name: Center
provenance_date: '2026-11-09'
provider_name: Center
provider_slug: center
slug: center-eligibility
source_date: '2026-11-09'
source_filename: center-eligibility.yml
source_heading: Eligibility
source_page: https://center.com/terms?lang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Center\naid: center\nurl: https://center.com/terms?lang=en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter a binding contract.\n- type: business\n  text: If you use Center for a business, you agree on behalf of that business and confirm you have authority to\n    do so.\nrestricted_uses:\n- summary: Not for emergencies\n  text: Center is not an emergency service and must not be relied on in an emergency.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/center/eligibility/center-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Center's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Personal Assistant
- SMS
- Messaging
- Artificial Intelligence
- Privacy
---
