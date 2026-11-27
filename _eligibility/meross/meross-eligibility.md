---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Services users, including Site visitors, App users, Product users, Cloud users, and other individuals who use our Services
    type: individual
  minimum_age:
    text: if you are a child under 16, please do not attempt to register for our Services or send any personal data about yourself to us. If you are under the age of 18 (or the age of legal majority where you live), you may use our Services only under the supervision of a parent or legal guardian
    value: '16'
  restricted_uses:
  - summary: Dangerous connections
    text: you will not connect any physical devices or third party services to the Services (or otherwise use the Services) in a manner that could be dangerous to you or to others
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be required to sign up for an account, provide a verifiable email address, and select a password or PIN number and user name
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Meross
provenance_date: '2026-11-10'
provider_name: Meross
provider_slug: meross
slug: meross-eligibility
source_date: '2026-11-10'
source_filename: meross-eligibility.yml
source_heading: Eligibility
source_page: https://www.meross.com/en-gc/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meross\naid: meross\nurl: https://www.meross.com/en-gc/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Services users, including Site visitors, App users, Product users, Cloud users, and other individuals who\n    use our Services\nrestricted_uses:\n- summary: Dangerous connections\n  text: you will not connect any physical devices or third party services to the Services (or otherwise use the\n    Services) in a manner that could be dangerous to you or to others\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: you may be required to sign up for an account, provide a verifiable email address, and select a password\n    or PIN number and user name\nminimum_age:\n  value: '16'\n  text: if you are a child under 16, please do not attempt to register for our Services or send any personal data\n    about yourself to us. If you are under the age of 18 (or the age of legal majority where you live), you may\n    use our Services only under the supervision of a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/meross/eligibility/meross-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Meross's own page on 2026-11-10.
synthetic: false
tags:
- Smart Home
- IoT
- Automation
- Consumer
- Hardware
---
