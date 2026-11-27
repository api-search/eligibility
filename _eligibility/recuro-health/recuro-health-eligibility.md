---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: To use the Application and the Healthcare Services, you must be located in one of the jurisdictions in which the Healthcare Services are available.
  entity_types:
  - text: By installing and/or using the Application, you represent and warrant that you are eighteen (18) years of age or older AND possess the legal right and ability, on behalf of yourself or a minor child of whom you are a parent or legal guardian
    type: individual
  minimum_age:
    text: you represent and warrant that you are eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: DO NOT USE THIS APPLICATION OR HEALTHCARE SERVICES FOR EMERGENCY MEDICAL NEEDS. If you experience a medical emergency, call 911 immediately.
  - summary: No life support or medical devices
    text: use the Application in connection with life support systems, human implantation, medical devices, or any application where failure or malfunction could lead to possible loss of life or catastrophic property damage
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
name: Recuro Health
provenance_date: '2026-11-10'
provider_name: Recuro Health
provider_slug: recuro-health
slug: recuro-health-eligibility
source_date: '2026-11-10'
source_filename: recuro-health-eligibility.yml
source_heading: Eligibility
source_page: https://recurohealth.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Recuro Health\naid: recuro-health\nurl: https://recurohealth.com/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: To use the Application and the Healthcare Services, you must be located in one of the jurisdictions in which\n    the Healthcare Services are available.\nentity_types:\n- type: individual\n  text: By installing and/or using the Application, you represent and warrant that you are eighteen (18) years of\n    age or older AND possess the legal right and ability, on behalf of yourself or a minor child of whom you are\n    a parent or legal guardian\nrestricted_uses:\n\
  - summary: Not for emergencies\n  text: DO NOT USE THIS APPLICATION OR HEALTHCARE SERVICES FOR EMERGENCY MEDICAL NEEDS. If you experience a medical\n    emergency, call 911 immediately.\n- summary: No life support or medical devices\n  text: use the Application in connection with life support systems, human implantation, medical devices, or any\n    application where failure or malfunction could lead to possible loss of life or catastrophic property damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/recuro-health/eligibility/recuro-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Recuro Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Virtual Care
- Digital Health
- Behavioral Health
- Primary Care
- Employee Benefits
- Health Plans
- Identity
---
