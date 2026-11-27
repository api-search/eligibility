---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are only available in the United States.
  entity_types:
  - text: Your account may only be used for your personal use.
    type: individual
  minimum_age:
    text: In order to create an account, you must be of the legal age to enter into a contract (i.e. be 18 in most states, or be an emancipated minor).
    value: '18'
  restricted_uses:
  - summary: No emergencies
    text: DO NOT USE THE SERVICES FOR EMERGENCIES. Our Services are not for medical emergencies or urgent situations.
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
name: Counsel Health
provenance_date: '2026-11-09'
provider_name: Counsel Health
provider_slug: counsel-health
slug: counsel-health-eligibility
source_date: '2026-11-09'
source_filename: counsel-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.counselhealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Counsel Health\naid: counsel-health\nurl: https://www.counselhealth.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are only available in the United States.\nentity_types:\n- type: individual\n  text: Your account may only be used for your personal use.\nrestricted_uses:\n- summary: No emergencies\n  text: DO NOT USE THE SERVICES FOR EMERGENCIES. Our Services are not for medical emergencies or urgent situations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to\
  \ create an account, you must be of the legal age to enter into a contract (i.e. be 18 in most\n    states, or be an emancipated minor).\n"
source_yaml_url: https://artifacts.apis.io/counsel-health/eligibility/counsel-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Counsel Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Healthcare
- Telehealth
- Primary Care
- Artificial Intelligence
- Embedded API
- Digital Health
---
