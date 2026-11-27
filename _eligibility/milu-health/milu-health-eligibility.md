---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Milu makes no representation that all products, services and/or material described on or through the Services are appropriate or available for use in locations outside the United States or all states and territories within the United States.
  entity_types:
  - text: By agreeing to these Terms or accessing or using the Services, you represent and warrant that you are at least 18 years old.
    type: individual
  minimum_age:
    text: you represent and warrant that you are at least 18 years old. If you are not at least 18 years old, you are not permitted to use the Services.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: THE SERVICES ARE NOT INTENDED FOR USE IN AN EMERGENCY.
  - summary: No use in legal disputes
    text: You are prohibited from using the Non-clinical Services in connection with any legal dispute, including but not limited to litigation, arbitration, claim for disability benefits, claim for worker’s compensation and/or malpractice claims.
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
name: Milu Health
provenance_date: '2026-11-10'
provider_name: Milu Health
provider_slug: milu-health
slug: milu-health-eligibility
source_date: '2026-11-10'
source_filename: milu-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.miluhealth.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Milu Health\naid: milu-health\nurl: https://www.miluhealth.com/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Milu makes no representation that all products, services and/or material described on or through the Services\n    are appropriate or available for use in locations outside the United States or all states and territories within\n    the United States.\nentity_types:\n- type: individual\n  text: By agreeing to these Terms or accessing or using the Services, you represent and warrant that you are at\n    least 18 years old.\nrestricted_uses:\n\
  - summary: Not for emergencies\n  text: THE SERVICES ARE NOT INTENDED FOR USE IN AN EMERGENCY.\n- summary: No use in legal disputes\n  text: You are prohibited from using the Non-clinical Services in connection with any legal dispute, including\n    but not limited to litigation, arbitration, claim for disability benefits, claim for worker’s compensation and/or\n    malpractice claims.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least 18 years old. If you are not at least 18 years old, you\n    are not permitted to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/milu-health/eligibility/milu-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Milu Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Health Savings
- Artificial Intelligence
- Employee Benefits
- Electronic Health Records
---
