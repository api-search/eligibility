---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The product information provided on our website is intended for residents of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not personalized medical advice
    text: We do not offer personalized medical advice or patient-specific treatment advice.
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
name: Vergent Bioscience
provenance_date: '2026-11-10'
provider_name: Vergent Bioscience
provider_slug: vergent-bioscience
slug: vergent-bioscience-eligibility
source_date: '2026-11-10'
source_filename: vergent-bioscience-eligibility.yml
source_heading: Eligibility
source_page: https://www.vergentbio.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vergent Bioscience\naid: vergent-bioscience\nurl: https://www.vergentbio.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The product information provided on our website is intended for residents of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Not personalized medical advice\n  text: We do not offer personalized medical advice or patient-specific treatment advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vergent-bioscience/eligibility/vergent-bioscience-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Vergent Bioscience's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Life Sciences
- Healthcare
- Medical Imaging
- Oncology
- Surgery
- Clinical Trials
- MCP
---
