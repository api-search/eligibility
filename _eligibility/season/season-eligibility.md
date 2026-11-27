---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are not available to users located outside the United States.
  entity_types:
  - text: In order to access the Platform and the Services, you represent and warrant that you are 18 years old or older.
    type: individual
  - text: you must be a licensed physician, nurse practitioner, or healthcare professional contracted or employed by the Medical Group
    type: other
  minimum_age:
    text: you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Not for medical emergencies
    text: Our Platform and the Services are not for medical emergencies or urgent situations.
  - summary: Commercial use without written consent
    text: or otherwise exploited for any commercial purpose without express written consent of Season Health.
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
name: Season Health
provenance_date: '2026-11-10'
provider_name: Season Health
provider_slug: season
slug: season-eligibility
source_date: '2026-11-10'
source_filename: season-eligibility.yml
source_heading: Eligibility
source_page: https://www.seasonhealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Season Health\naid: season\nurl: https://www.seasonhealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: In order to access the Platform and the Services, you represent and warrant that you are 18 years old or\n    older.\n- type: other\n  text: you must be a licensed physician, nurse practitioner, or healthcare professional contracted or employed\n    by the Medical Group\nrestricted_uses:\n- summary: Not for medical emergencies\n\
  \  text: Our Platform and the Services are not for medical emergencies or urgent situations.\n- summary: Commercial use without written consent\n  text: or otherwise exploited for any commercial purpose without express written consent of Season Health.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/season/eligibility/season-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Season Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Nutrition
- Food as Medicine
- Digital Health
- Chronic Care
- Telehealth
---
