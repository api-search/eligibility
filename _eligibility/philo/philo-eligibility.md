---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are licensed to you solely for your private, non-exclusive, non-transferable, non-commercial, limited, and revocable use solely in the United States of America and its territories and commonwealths.
  entity_types:
  - text: You must be at least 18 1 to register for an account with us
    type: individual
  minimum_age:
    text: You must be at least 18 1 to register for an account with us ("Account") and must register for an Account to subscribe to our Philo Subscription Service.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: non-commercial, limited, and revocable use
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
name: Philo
provenance_date: '2026-11-10'
provider_name: Philo
provider_slug: philo
slug: philo-eligibility
source_date: '2026-11-10'
source_filename: philo-eligibility.yml
source_heading: Eligibility
source_page: https://www.philo.com/about/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Philo\naid: philo\nurl: https://www.philo.com/about/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are licensed to you solely for your private, non-exclusive, non-transferable, non-commercial,\n    limited, and revocable use solely in the United States of America and its territories and commonwealths.\nentity_types:\n- type: individual\n  text: You must be at least 18 1 to register for an account with us\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: non-commercial, limited, and revocable use\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 1 to register for an account with us (\"Account\") and must register for an Account\n    to subscribe to our Philo Subscription Service.\n"
source_yaml_url: https://artifacts.apis.io/philo/eligibility/philo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Philo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Streaming
- Television
- Video
- Media
- Entertainment
- Live TV
- Advertising
- Consumer
---
