---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is hosted in the United States of America and is intended for use by residents of the United States of America only.
  entity_types:
  - text: Use of the Site by anyone under the age of 18 is prohibited.
    type: individual
  minimum_age:
    text: Use of the Site by anyone under the age of 18 is prohibited.
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: THE CONTENT OF THE SITE IS NOT INTENDED IN ANY WAY TO SUBSTITUTE FOR PROFESSIONAL MEDICAL ADVICE AND SHOULD NOT BE RELIED ON FOR MEDICAL DIAGNOSIS OR TREATMENT.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some of the Site may require registration. Each registration is for a single user only.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aulos
provenance_date: '2026-11-09'
provider_name: Aulos
provider_slug: aulos
slug: aulos-eligibility
source_date: '2026-11-09'
source_filename: aulos-eligibility.yml
source_heading: Eligibility
source_page: https://aulosbio.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aulos\naid: aulos\nurl: https://aulosbio.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is hosted in the United States of America and is intended for use by residents of the United States\n    of America only.\nentity_types:\n- type: individual\n  text: Use of the Site by anyone under the age of 18 is prohibited.\nrestricted_uses:\n- summary: Not medical advice\n  text: THE CONTENT OF THE SITE IS NOT INTENDED IN ANY WAY TO SUBSTITUTE FOR PROFESSIONAL MEDICAL ADVICE AND SHOULD\n    NOT BE RELIED ON FOR MEDICAL DIAGNOSIS OR TREATMENT.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some of the Site may require registration. Each registration is for a single user only.\nminimum_age:\n  value: '18'\n  text: Use of the Site by anyone under the age of 18 is prohibited.\n"
source_yaml_url: https://artifacts.apis.io/aulos/eligibility/aulos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Aulos's own page on 2026-11-09.
synthetic: false
tags:
- Oncology
- Biopharma
- Antibody Therapeutics
- IL-2 Therapeutics
- Clinical Trials
---
