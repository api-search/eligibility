---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: General Terms and Conditions for Business Associates ("GTCs-B2B")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Operator must not process health or sensitive data
    text: the Operator undertakes not to process any health-related or other sensitive data via the Eversports cloud software or Eversports platform.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Operator further acknowledges that Eversports does not verify the identity or age of Users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Eversports
provenance_date: '2026-11-09'
provider_name: Eversports
provider_slug: eversports
slug: eversports-eligibility
source_date: '2026-11-09'
source_filename: eversports-eligibility.yml
source_heading: Eligibility
source_page: https://www.eversportsmanager.com/gtc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eversports\naid: eversports\nurl: https://www.eversportsmanager.com/gtc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: General Terms and Conditions for Business Associates (\"GTCs-B2B\")\nrestricted_uses:\n- summary: Operator must not process health or sensitive data\n  text: the Operator undertakes not to process any health-related or other sensitive data via the Eversports cloud\n    software or Eversports platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Operator further acknowledges that\
  \ Eversports does not verify the identity or age of Users.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eversports/eligibility/eversports-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Eversports's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sports
- Fitness
- Booking
- Scheduling
- Wellness
- GraphQL
- Reservations
- Event
---
