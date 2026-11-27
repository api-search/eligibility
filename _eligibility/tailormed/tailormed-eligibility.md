---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Service may not be exported or re-exported into any U.S. or Israel embargoed countries or to anyone on the U.S. Department of Commerce Denied Person's List or Entity List or the U.S. Treasury Department's list of Specially Designated Nationals.
  minimum_age:
    text: You may not use the Services if you are a Minor
    value: not stated
  restricted_uses:
  - summary: No medical advice
    text: THE SERVICES DO NOT PROVIDE MEDICAL ADVICE.
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
name: TailorMed
provenance_date: '2026-11-10'
provider_name: TailorMed
provider_slug: tailormed
slug: tailormed-eligibility
source_date: '2026-11-10'
source_filename: tailormed-eligibility.yml
source_heading: Eligibility
source_page: https://www.tailormed.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TailorMed\naid: tailormed\nurl: https://www.tailormed.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Service may not be exported or re-exported into any U.S. or Israel embargoed countries or to anyone on the\n    U.S. Department of Commerce Denied Person's List or Entity List or the U.S. Treasury Department's list of Specially\n    Designated Nationals.\nentity_types: []\nrestricted_uses:\n- summary: No medical advice\n  text: THE SERVICES DO NOT PROVIDE MEDICAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: not stated\n  text: You may not use the Services if you are a Minor\n"
source_yaml_url: https://artifacts.apis.io/tailormed/eligibility/tailormed-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from TailorMed's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health IT
- Medication Access
- Medication Affordability
- Financial Navigation
- Patient Assistance
- Pharmacy
- Oncology
- Revenue Cycle
- HL7
- FHIR
- Life Sciences
---
