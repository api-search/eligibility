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
  - summary: No personalized medical advice
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
name: Code Biotherapeutics
provenance_date: '2026-11-09'
provider_name: Code Biotherapeutics
provider_slug: code-biotherapeutics
slug: code-biotherapeutics-eligibility
source_date: '2026-11-09'
source_filename: code-biotherapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://www.codebiotx.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Code Biotherapeutics\naid: code-biotherapeutics\nurl: https://www.codebiotx.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The product information provided on our website is intended for residents of the United States.\nentity_types: []\nrestricted_uses:\n- summary: No personalized medical advice\n  text: We do not offer personalized medical advice or patient-specific treatment advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/code-biotherapeutics/eligibility/code-biotherapeutics-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Code Biotherapeutics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Genetic Medicine
- Gene Therapy
- Life Sciences
- Pharmaceuticals
- Rare Disease
- Drug Discovery
---
