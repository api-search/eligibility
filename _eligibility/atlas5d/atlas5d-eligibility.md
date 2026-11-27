---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Subscriber confirms and agrees that the Subscriber is at least 18 years old.
    type: individual
  minimum_age:
    text: By registering and creating an account, Subscriber confirms and agrees that the Subscriber is at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Not a medical device
    text: the Atlas5D Solution is not a medical device and reports do not constitute medical advice
  - summary: Consent of monitored persons required
    text: Subscriber shall obtain all consents from, and provide all notices to, each Monitored Person and each Recipient as legally required
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
name: Atlas5D
provenance_date: '2026-11-09'
provider_name: Atlas5D
provider_slug: atlas5d
slug: atlas5d-eligibility
source_date: '2026-11-09'
source_filename: atlas5d-eligibility.yml
source_heading: Eligibility
source_page: https://atlas5d.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlas5D\naid: atlas5d\nurl: https://atlas5d.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Subscriber confirms and agrees that the Subscriber is at least 18 years old.\nrestricted_uses:\n- summary: Not a medical device\n  text: the Atlas5D Solution is not a medical device and reports do not constitute medical advice\n- summary: Consent of monitored persons required\n  text: Subscriber shall obtain all consents from, and provide all notices to, each Monitored Person and each Recipient\n    as legally required\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By registering and creating an account, Subscriber confirms and agrees that the Subscriber is at least 18\n    years old.\n"
source_yaml_url: https://artifacts.apis.io/atlas5d/eligibility/atlas5d-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Atlas5D's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Tech
- Remote Patient Monitoring
- Ambient Computing
- Sensors
- Aging in Place
- Clinical Trials
- Digital Health
---
