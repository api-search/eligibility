---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: the ones involving a consultation with a practitioner are only available when you are in Canada.
  entity_types:
  - text: Members, meaning individuals who access Dialogue services through a benefits program offered by an employer, association, or other sponsoring organization.
    type: individual
  minimum_age:
    text: If you are 14 or older and able to consent , you must create and manage your own account.
    value: '14'
  restricted_uses:
  - summary: Not for emergencies
    text: The services are not intended for emergencies.
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
name: Dialogue
provenance_date: '2026-11-09'
provider_name: Dialogue
provider_slug: dialogue
slug: dialogue-eligibility
source_date: '2026-11-09'
source_filename: dialogue-eligibility.yml
source_heading: Eligibility
source_page: https://www.dialogue.co/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dialogue\naid: dialogue\nurl: https://www.dialogue.co/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: the ones involving a consultation with a practitioner are only available when you are in Canada.\nentity_types:\n- type: individual\n  text: Members, meaning individuals who access Dialogue services through a benefits program offered by an employer,\n    association, or other sponsoring organization.\nrestricted_uses:\n- summary: Not for emergencies\n  text: The services are not intended for emergencies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '14'\n  text: If you are 14 or older and able to consent , you must create and manage your own account.\n"
source_yaml_url: https://artifacts.apis.io/dialogue/eligibility/dialogue-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dialogue's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Virtual Care
- Mental Health
- Employee Assistance Program
- Wellness
- Consumer
- Canada
---
