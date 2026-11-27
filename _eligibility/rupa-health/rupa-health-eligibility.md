---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: all purchases are intended for final delivery to locations within the United States, but excluding New Jersey, New York, and Rhode Island.
  entity_types:
  - text: lab company or individual/patient accessing the Rupa proprietary platform
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not medical advice
    text: USE OF THE SITE IS NOT A SUBSTITUTE FOR PROFESSIONAL DIAGNOSIS OR TREATMENT AND RELIANCE ON ANY INFORMATION PROVIDED BY RUPA IS SOLELY AT YOUR OWN RISK.
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
name: Rupa Health
provenance_date: '2026-11-10'
provider_name: Rupa Health
provider_slug: rupa-health
slug: rupa-health-eligibility
source_date: '2026-11-10'
source_filename: rupa-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.rupahealth.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rupa Health\naid: rupa-health\nurl: https://www.rupahealth.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: all purchases are intended for final delivery to locations within the United States, but excluding New Jersey,\n    New York, and Rhode Island.\nentity_types:\n- type: individual\n  text: lab company or individual/patient accessing the Rupa proprietary platform\nrestricted_uses:\n- summary: Not medical advice\n  text: USE OF THE SITE IS NOT A SUBSTITUTE FOR PROFESSIONAL DIAGNOSIS OR TREATMENT AND RELIANCE ON ANY INFORMATION\n    PROVIDED BY RUPA\
  \ IS SOLELY AT YOUR OWN RISK.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rupa-health/eligibility/rupa-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Rupa Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Lab Testing
- Functional Medicine
- Diagnostics
- Health
- Practitioner Tools
---
