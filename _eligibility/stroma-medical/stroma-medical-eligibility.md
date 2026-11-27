---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Strōma Laser System is an investigational device, and it is not available for sale or use in the United States.
  entity_types:
  - text: You may use the Service for personal, non-commercial use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: You may use the Service for personal, non-commercial use only.
  - summary: Not for diagnosis or treatment
    text: should not be used to diagnose or treat a health or vision problem without consulting your physician.
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
name: Stroma Medical
provenance_date: '2026-11-10'
provider_name: Stroma Medical
provider_slug: stroma-medical
slug: stroma-medical-eligibility
source_date: '2026-11-10'
source_filename: stroma-medical-eligibility.yml
source_heading: Eligibility
source_page: https://www.stromamedical.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stroma Medical\naid: stroma-medical\nurl: https://www.stromamedical.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Strōma Laser System is an investigational device, and it is not available for sale or use in the United\n    States.\nentity_types:\n- type: individual\n  text: You may use the Service for personal, non-commercial use only.\nrestricted_uses:\n- summary: No commercial use\n  text: You may use the Service for personal, non-commercial use only.\n- summary: Not for diagnosis or treatment\n  text: should not be used to diagnose or treat a health or\
  \ vision problem without consulting your physician.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stroma-medical/eligibility/stroma-medical-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Stroma Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Healthcare
- Ophthalmology
- Laser Systems
- Clinical Stage
- Surgical Devices
- Life Sciences
---
