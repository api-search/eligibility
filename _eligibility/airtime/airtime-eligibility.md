---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using an Airtime for Teams account (“ Teams ”), your use of the Services is additionally governed by the Teams Agreement
    type: business
  minimum_age:
    text: You may not create an account, use, or access the Services if you are under 13 years of age. If you are under 18 years of age, you may only use the Services with the prior consent of a parent or legal guardian
    value: '13'
  restricted_uses:
  - summary: Unauthorized or illegal use
    text: use the Services for any unauthorized or illegal purposes
  - summary: Recording laws
    text: You are solely responsible for complying with all applicable laws in the relevant jurisdictions while using any recording functionality
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
name: Airtime
provenance_date: '2026-11-09'
provider_name: Airtime
provider_slug: airtime
slug: airtime-eligibility
source_date: '2026-11-09'
source_filename: airtime-eligibility.yml
source_heading: Eligibility
source_page: https://www.airtime.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Airtime\naid: airtime\nurl: https://www.airtime.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using an Airtime for Teams account (“ Teams ”), your use of the Services is additionally governed\n    by the Teams Agreement\nrestricted_uses:\n- summary: Unauthorized or illegal use\n  text: use the Services for any unauthorized or illegal purposes\n- summary: Recording laws\n  text: You are solely responsible for complying with all applicable laws in the relevant jurisdictions while using\n    any recording\
  \ functionality\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may not create an account, use, or access the Services if you are under 13 years of age. If you are\n    under 18 years of age, you may only use the Services with the prior consent of a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/airtime/eligibility/airtime-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Airtime's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Video
- Productivity
- Collaboration
- Screen Recording
- Presentations
- Remote Work
---
