---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using the Service, you represent, acknowledge, and agree that you are of age under the laws of your jurisdiction (usually 18+ years) and/or lawfully able to enter into contracts.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: THE USE OF OUR SERVICE IS NOT APPROPRIATE FOR EMERGENCIES.
  - summary: No prescription fulfilment
    text: You cannot fill prescriptions through the Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We do not confirm the credentials of Providers (including health care providers) using our Service and do not validate that they are in good standing with their respective licensure board(s).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scene Health
provenance_date: '2026-11-10'
provider_name: Scene Health
provider_slug: scene-health
slug: scene-health-eligibility
source_date: '2026-11-10'
source_filename: scene-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.scene.health/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scene Health\naid: scene-health\nurl: https://www.scene.health/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for emergencies\n  text: THE USE OF OUR SERVICE IS NOT APPROPRIATE FOR EMERGENCIES.\n- summary: No prescription fulfilment\n  text: You cannot fill prescriptions through the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We do not confirm the credentials of Providers (including health care providers) using our Service and do\n    not validate that\
  \ they are in good standing with their respective licensure board(s).\nminimum_age:\n  value: '18'\n  text: By using the Service, you represent, acknowledge, and agree that you are of age under the laws of your jurisdiction\n    (usually 18+ years) and/or lawfully able to enter into contracts.\n"
source_yaml_url: https://artifacts.apis.io/scene-health/eligibility/scene-health-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Scene Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Medication Adherence
- Patient Engagement
- Telehealth
- Medicaid
- Public Health
- Clinical Trials
---
