---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Although accessible by others, the Services (which include content) are intended for access and use only by U.S. customers.
  entity_types:
  - text: provides the Applications for your personal use.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older and reside in the United States to use our Text Messaging.
    value: '18'
  restricted_uses:
  - summary: Sole personal use only
    text: You will only use the Services for your sole, personal use and you will not resell them to a third party;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we are entitled at all times to verify the information provided and to deny your use of the Services at any time for any reason or no reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Heartbeat Health
provenance_date: '2026-11-09'
provider_name: Heartbeat Health
provider_slug: heartbeat-health
slug: heartbeat-health-eligibility
source_date: '2026-11-09'
source_filename: heartbeat-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.heartbeathealth.com/general-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Heartbeat Health\naid: heartbeat-health\nurl: https://www.heartbeathealth.com/general-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Although accessible by others, the Services (which include content) are intended for access and use only\n    by U.S. customers.\nentity_types:\n- type: individual\n  text: provides the Applications for your personal use.\nrestricted_uses:\n- summary: Sole personal use only\n  text: You will only use the Services for your sole, personal use and you will not resell them to a third party;\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: we are entitled at all times to verify the information provided and to deny your use of the Services at\n    any time for any reason or no reason.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older and reside in the United States to use our Text Messaging.\n"
source_yaml_url: https://artifacts.apis.io/heartbeat-health/eligibility/heartbeat-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Heartbeat Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Wellness
- Cardiology
- Telehealth
- Remote Patient Monitoring
- Digital Health
- Cardiovascular Care
---
