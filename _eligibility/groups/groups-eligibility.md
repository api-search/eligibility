---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Platform is limited exclusively to users located in states within the United States where the Platform is available. Services are not available to users located outside the United States.
  entity_types:
  - text: You represent and warrant that you are 18 years old or older.
    type: individual
  minimum_age:
    text: you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: No emergencies
    text: Our Platform and the Services are not for medical emergencies or urgent situations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Platform requires a valid phone number and other information to initially set up your access to the Platform
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Groups
provenance_date: '2026-11-09'
provider_name: Groups
provider_slug: groups
slug: groups-eligibility
source_date: '2026-11-09'
source_filename: groups-eligibility.yml
source_heading: Eligibility
source_page: https://www.joingroups.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Groups\naid: groups\nurl: https://www.joingroups.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are 18 years old or older.\nrestricted_uses:\n- summary: No emergencies\n  text: Our Platform and the Services are not for medical emergencies or urgent situations.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Platform requires a valid phone number and other information to initially set up your access to the\n    Platform\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/groups/eligibility/groups-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Groups's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Addiction Treatment
- Opioid Use Disorder
- Medication-Assisted Treatment
- Telehealth
- Behavioral Health
- Recovery
---
