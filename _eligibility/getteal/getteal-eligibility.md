---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are not available to users located outside the United States.
  minimum_age:
    text: you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Emergencies
    text: Our Platform and the Services are not for medical emergencies or urgent situations.
  - summary: Personal prescriptions only
    text: You agree that any prescriptions that you acquire from a Provider will be solely for your personal use.
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
name: Getteal
provenance_date: '2026-11-09'
provider_name: Getteal
provider_slug: getteal
slug: getteal-eligibility
source_date: '2026-11-09'
source_filename: getteal-eligibility.yml
source_heading: Eligibility
source_page: https://www.getteal.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Getteal\naid: getteal\nurl: https://www.getteal.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to users located outside the United States.\nentity_types: []\nrestricted_uses:\n- summary: Emergencies\n  text: Our Platform and the Services are not for medical emergencies or urgent situations.\n- summary: Personal prescriptions only\n  text: You agree that any prescriptions that you acquire from a Provider will be solely for your personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: you represent and warrant that you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/getteal/eligibility/getteal-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Getteal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Women's Health
- Femtech
- Diagnostics
- Cervical Cancer Screening
- Telehealth
---
