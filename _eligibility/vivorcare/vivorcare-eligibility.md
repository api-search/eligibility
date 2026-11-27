---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services for use only by persons located in the United States.
  entity_types:
  - text: Our Services are intended for use by you only if you are 18 years of age or over.
    type: individual
  minimum_age:
    text: Our Services are intended for use by you only if you are 18 years of age or over.
    value: '18'
  restricted_uses:
  - summary: Not for medical emergencies
    text: THE SERVICES ARE NOT INTENDED FOR USE IN A MEDICAL EMERGENCY.
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
name: VivorCare
provenance_date: '2026-11-10'
provider_name: VivorCare
provider_slug: vivorcare
slug: vivorcare-eligibility
source_date: '2026-11-10'
source_filename: vivorcare-eligibility.yml
source_heading: Eligibility
source_page: https://www.oncoverycare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VivorCare\naid: vivorcare\nurl: https://www.oncoverycare.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: Our Services are intended for use by you only if you are 18 years of age or over.\nrestricted_uses:\n- summary: Not for medical emergencies\n  text: THE SERVICES ARE NOT INTENDED FOR USE IN A MEDICAL EMERGENCY.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Services\
  \ are intended for use by you only if you are 18 years of age or over.\n"
source_yaml_url: https://artifacts.apis.io/vivorcare/eligibility/vivorcare-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from VivorCare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Cancer Survivorship
- Oncology
- Telehealth
- Virtual Care
- Digital Health
- Techstars
---
