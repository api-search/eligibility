---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: registered to provide certain health services in one or more provinces or territories in Canada
  entity_types:
  - text: To use the Platforms, you must be 18 years of age or older.
    type: individual
  - text: IF YOU ARE ACCESSING OR USING THE PLATFORM ON BEHALF OF ANOTHER PERSON OR A CORPORATE ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND SUCH PERSON OR ENTITY TO THESE TERMS OF USE.
    type: business
  minimum_age:
    text: To use the Platforms, you must be 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: No medical emergencies
    text: DO NOT USE THE PLATFORMS FOR MEDICAL EMERGENCIES.
  - summary: No controlled substances prescribing
    text: HCPs are not permitted to prescribe certain kinds of medication including narcotics, controlled substances or other types of controlled medications
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
name: Tia Health
provenance_date: '2026-11-10'
provider_name: Tia Health
provider_slug: tia-health
slug: tia-health-eligibility
source_date: '2026-11-10'
source_filename: tia-health-eligibility.yml
source_heading: Eligibility
source_page: https://tiahealth.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tia Health\naid: tia-health\nurl: https://tiahealth.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: registered to provide certain health services in one or more provinces or territories in Canada\nentity_types:\n- type: individual\n  text: To use the Platforms, you must be 18 years of age or older.\n- type: business\n  text: IF YOU ARE ACCESSING OR USING THE PLATFORM ON BEHALF OF ANOTHER PERSON OR A CORPORATE ENTITY, YOU REPRESENT\n    AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND SUCH PERSON OR ENTITY TO THESE TERMS OF USE.\nrestricted_uses:\n- summary:\
  \ No medical emergencies\n  text: DO NOT USE THE PLATFORMS FOR MEDICAL EMERGENCIES.\n- summary: No controlled substances prescribing\n  text: HCPs are not permitted to prescribe certain kinds of medication including narcotics, controlled substances\n    or other types of controlled medications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Platforms, you must be 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/tia-health/eligibility/tia-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Tia Health's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Canada
- Telehealth
- Virtual Care
- Digital Health
- Primary Care
- Mental Health
- Prescriptions
---
