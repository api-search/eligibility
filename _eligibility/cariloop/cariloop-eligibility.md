---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: We provide this Platform for use only by persons located in the United States and Canada, except that any use of the Backup Care Program is only available for use by persons located in the United States.
  entity_types:
  - text: This Platform is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Platform is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: No emergencies
    text: OUR PLATFORM, INCLUDING THE BACKUP CARE PROGRAM, IS NOT FOR MEDICAL EMERGENCIES OR OTHER URGENT SITUATIONS
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
name: Cariloop
provenance_date: '2026-11-09'
provider_name: Cariloop
provider_slug: cariloop
slug: cariloop-eligibility
source_date: '2026-11-09'
source_filename: cariloop-eligibility.yml
source_heading: Eligibility
source_page: https://cariloop.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cariloop\naid: cariloop\nurl: https://cariloop.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: We provide this Platform for use only by persons located in the United States and Canada, except that any\n    use of the Backup Care Program is only available for use by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Platform is offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: No emergencies\n  text: OUR PLATFORM, INCLUDING THE BACKUP CARE PROGRAM, IS NOT FOR MEDICAL\
  \ EMERGENCIES OR OTHER URGENT SITUATIONS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Platform is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/cariloop/eligibility/cariloop-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cariloop's own page on 2026-11-09.
synthetic: false
tags:
- Caregiving
- Employee Benefits
- Back-Up Care
- Caregiver Support Platform
- Coaching
- Employer Solutions
---
