---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: Illegal access
    text: Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.
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
name: Pattern Bioscience
provenance_date: '2026-11-10'
provider_name: Pattern Bioscience
provider_slug: pattern-bioscience
slug: pattern-bioscience-eligibility
source_date: '2026-11-10'
source_filename: pattern-bioscience-eligibility.yml
source_heading: Eligibility
source_page: https://pattern.bio/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pattern Bioscience\naid: pattern-bioscience\nurl: https://pattern.bio/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Illegal access\n  text: Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/pattern-bioscience/eligibility/pattern-bioscience-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pattern Bioscience's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Diagnostics
- Healthcare
- Medical Devices
- In Vitro Diagnostics
- Microbiology
- Antimicrobial Resistance
- Life Sciences
- Machine Learning
- Austin
---
