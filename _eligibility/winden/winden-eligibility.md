---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may only apply for an Account, and use the applicable Services under such Account, if you are a legal entity formed and registered in the United States
  entity_types:
  - text: You will use your Account exclusively for business purposes and not for any personal, family, or household use;
    type: business
  - text: Individual consumers and companies organized and registered outside the United States are not permitted to use or attempt to open or use an Account or the Services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited businesses
    text: 'You must not use Winden''s services for the following activities:'
  - summary: Consumer or non-commercial use
    text: Any use of or access to the Services for consumer or non-commercial purposes or by any individual who is not your employee, contractor, agent, or other individual permitted to use your Account on your behalf (" User ") is strictly prohibited
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
name: Winden
provenance_date: '2026-11-10'
provider_name: Winden
provider_slug: winden
slug: winden-eligibility
source_date: '2026-11-10'
source_filename: winden-eligibility.yml
source_heading: Eligibility
source_page: https://winden.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Winden\naid: winden\nurl: https://winden.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may only apply for an Account, and use the applicable Services under such Account, if you are a legal\n    entity formed and registered in the United States\nentity_types:\n- type: business\n  text: You will use your Account exclusively for business purposes and not for any personal, family, or household\n    use;\n- type: individual\n  text: Individual consumers and companies organized and registered outside the United States are not permitted\n    to use\
  \ or attempt to open or use an Account or the Services.\nrestricted_uses:\n- summary: Prohibited businesses\n  text: 'You must not use Winden''s services for the following activities:'\n- summary: Consumer or non-commercial use\n  text: Any use of or access to the Services for consumer or non-commercial purposes or by any individual who is\n    not your employee, contractor, agent, or other individual permitted to use your Account on your behalf (\" User\n    \") is strictly prohibited\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/winden/eligibility/winden-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Winden's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Business Banking
- Credit Cards
- Payments
- Cashback
- Small Business
- Corporate Cards
---
