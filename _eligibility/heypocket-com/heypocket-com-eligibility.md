---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are offered only to individuals who are at least 18 years of age and in jurisdictions where the Services are legally permitted. Access to the Services may not be legal by certain persons or in certain countries; if you access the Services from outside the United States, you do so on your own initiative and are responsible for compliance with local laws.
  entity_types:
  - text: The Services are offered only to individuals who are at least 18 years of age and in jurisdictions where the Services are legally permitted.
    type: individual
  minimum_age:
    text: The Services are offered only to individuals who are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Recording others without consent
    text: You are solely responsible for complying with all applicable recording, wiretap, privacy, and data-protection laws, which may require the consent of all parties to a conversation.
  - summary: Exploiting minors
    text: For the purpose of exploiting, harming, or attempting to exploit or harm minors in any way by exposing them to inappropriate content, asking for personally identifiable information, or otherwise.
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
name: Pocket
provenance_date: '2026-11-09'
provider_name: Pocket
provider_slug: heypocket-com
slug: heypocket-com-eligibility
source_date: '2026-11-09'
source_filename: heypocket-com-eligibility.yml
source_heading: Eligibility
source_page: https://heypocket.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pocket\naid: heypocket-com\nurl: https://heypocket.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are offered only to individuals who are at least 18 years of age and in jurisdictions where\n    the Services are legally permitted. Access to the Services may not be legal by certain persons or in certain\n    countries; if you access the Services from outside the United States, you do so on your own initiative and are\n    responsible for compliance with local laws.\nentity_types:\n- type: individual\n  text: The Services are offered only to individuals\
  \ who are at least 18 years of age and in jurisdictions where\n    the Services are legally permitted.\nrestricted_uses:\n- summary: Recording others without consent\n  text: You are solely responsible for complying with all applicable recording, wiretap, privacy, and data-protection\n    laws, which may require the consent of all parties to a conversation.\n- summary: Exploiting minors\n  text: For the purpose of exploiting, harming, or attempting to exploit or harm minors in any way by exposing them\n    to inappropriate content, asking for personally identifiable information, or otherwise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are offered only to individuals who are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/heypocket-com/eligibility/heypocket-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pocket's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Artificial Intelligence
- Personal Finance
- Budgeting
---
