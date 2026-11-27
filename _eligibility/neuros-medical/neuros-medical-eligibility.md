---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site contains information regarding Neuros Medical and its products and services available within the United States. This Site is intended for use by residents in the United States.
  minimum_age:
    text: THIS SITE IS INTENDED FOR USE BY INDIVIDUALS 18 YEARS OF AGE OR OLDER.
    value: '18'
  restricted_uses:
  - summary: No medical or professional advice
    text: THIS WEBSITE DOES NOT PROVIDE MEDICAL ADVICE OR PROFESSIONAL ADVICE.
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
name: Neuros Medical
provenance_date: '2026-11-10'
provider_name: Neuros Medical
provider_slug: neuros-medical
slug: neuros-medical-eligibility
source_date: '2026-11-10'
source_filename: neuros-medical-eligibility.yml
source_heading: Eligibility
source_page: https://www.neurosmedical.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Neuros Medical\naid: neuros-medical\nurl: https://www.neurosmedical.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site contains information regarding Neuros Medical and its products and services available within the\n    United States. This Site is intended for use by residents in the United States.\nentity_types: []\nrestricted_uses:\n- summary: No medical or professional advice\n  text: THIS WEBSITE DOES NOT PROVIDE MEDICAL ADVICE OR PROFESSIONAL ADVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: THIS SITE IS INTENDED FOR USE BY INDIVIDUALS 18 YEARS OF AGE OR OLDER.\n"
source_yaml_url: https://artifacts.apis.io/neuros-medical/eligibility/neuros-medical-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Neuros Medical's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Neuromodulation
- Neurostimulation
- Pain Management
- Healthcare
- Implantable Devices
- Life Sciences
---
