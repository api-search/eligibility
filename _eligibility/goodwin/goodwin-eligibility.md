---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
  - summary: No automated access
    text: Use any robot, spider, or other automatic device, process, or means to access the Website for any purpose, including monitoring or copying any of the material on the Website.
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
name: Goodwin
provenance_date: '2026-11-09'
provider_name: Goodwin
provider_slug: goodwin
slug: goodwin-eligibility
source_date: '2026-11-09'
source_filename: goodwin-eligibility.yml
source_heading: Eligibility
source_page: https://www.teamgoodwin.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goodwin\naid: goodwin\nurl: https://www.teamgoodwin.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.\n- summary: No automated access\n  text: Use any robot, spider, or other automatic device, process, or means\
  \ to access the Website for any purpose,\n    including monitoring or copying any of the material on the Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/goodwin/eligibility/goodwin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Goodwin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Aviation
- Charter Aviation
- Private Aviation
- Travel
- Payments
- Software-as-a-Service
- B2B
---
