---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no claims that the materials are appropriate or may be downloaded outside of the United States.
  entity_types:
  - text: You represent that you are 18 years or older.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical advice
    text: 'THE COMPANY: (1) IS NOT PROVIDING ANY MEDICAL CARE, MEDICAL OPINION, MEDICAL ADVICE, TREATMENT, OR DIAGNOSIS'
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
name: Ossium Health
provenance_date: '2026-11-10'
provider_name: Ossium Health
provider_slug: ossium-health
slug: ossium-health-eligibility
source_date: '2026-11-10'
source_filename: ossium-health-eligibility.yml
source_heading: Eligibility
source_page: https://ossiumhealth.com/legal-policies/#terms_of_use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ossium Health\naid: ossium-health\nurl: https://ossiumhealth.com/legal-policies/#terms_of_use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no claims that the materials are appropriate or may be downloaded outside of the United States.\nentity_types:\n- type: individual\n  text: You represent that you are 18 years or older.\nrestricted_uses:\n- summary: No medical advice\n  text: 'THE COMPANY: (1) IS NOT PROVIDING ANY MEDICAL CARE, MEDICAL OPINION, MEDICAL ADVICE, TREATMENT, OR DIAGNOSIS'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ossium-health/eligibility/ossium-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Ossium Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Life Sciences
- Cell Therapy
- Regenerative Medicine
- Healthcare
- Bioengineering
---
