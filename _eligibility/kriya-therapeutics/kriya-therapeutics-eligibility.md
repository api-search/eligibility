---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise specified, the information on the Site is intended only for residents of the United States.
  entity_types:
  - text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  minimum_age:
    text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
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
name: Kriya Therapeutics
provenance_date: '2026-11-09'
provider_name: Kriya Therapeutics
provider_slug: kriya-therapeutics
slug: kriya-therapeutics-eligibility
source_date: '2026-11-09'
source_filename: kriya-therapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://www.kriyatx.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kriya Therapeutics\naid: kriya-therapeutics\nurl: https://www.kriyatx.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise specified, the information on the Site is intended only for residents of the United States.\nentity_types:\n- type: individual\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Site or accept the Terms if you\
  \ are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/kriya-therapeutics/eligibility/kriya-therapeutics-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Kriya Therapeutics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Gene Therapy
- AAV
- Ophthalmology
- Metabolic Disease
- Neurology
- Life Sciences
- Clinical Trials
- Biomanufacturing
- content-api
---
