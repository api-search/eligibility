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
  - text: In order to access the Platform and the Services, you represent and warrant that you are 18years old or older.
    type: individual
  minimum_age:
    text: In order to access the Platform and the Services, you represent and warrant that you are 18years old or older.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: Our Platform is not for medical emergencies or urgent situations.
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
name: Firefly Health
provenance_date: '2026-11-09'
provider_name: Firefly Health
provider_slug: firefly-health
slug: firefly-health-eligibility
source_date: '2026-11-09'
source_filename: firefly-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.fireflyhealth.com/terms-of-use?redirected=true
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Firefly Health\naid: firefly-health\nurl: https://www.fireflyhealth.com/terms-of-use?redirected=true\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: In order to access the Platform and the Services, you represent and warrant that you are 18years old or\n    older.\nrestricted_uses:\n- summary: Not for emergencies\n  text:\
  \ Our Platform is not for medical emergencies or urgent situations.\n- summary: Personal prescriptions only\n  text: You agree that any prescriptions that you acquire from a Provider will be solely for your personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to access the Platform and the Services, you represent and warrant that you are 18years old or\n    older.\n"
source_yaml_url: https://artifacts.apis.io/firefly-health/eligibility/firefly-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Firefly Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Plans
- Virtual Care
- Primary Care
- Telehealth
- Health Insurance
- Employee Benefits
- Digital Health
---
