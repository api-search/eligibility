---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: This website and the information provided on it are for the use of permanent residents of the United Kingdom only (for the purposes of this website the United Kingdom excludes the Channel Islands).
  entity_types:
  - text: This website and the information provided on it are for the use of permanent residents of the United Kingdom only
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Vitality
provenance_date: '2026-11-10'
provider_name: Vitality
provider_slug: vitality-uk
slug: vitality-uk-eligibility
source_date: '2026-11-10'
source_filename: vitality-uk-eligibility.yml
source_heading: Eligibility
source_page: https://www.vitality.co.uk/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vitality\naid: vitality-uk\nurl: https://www.vitality.co.uk/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: This website and the information provided on it are for the use of permanent residents of the United Kingdom\n    only (for the purposes of this website the United Kingdom excludes the Channel Islands).\nentity_types:\n- type: individual\n  text: This website and the information provided on it are for the use of permanent residents of the United Kingdom\n    only\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vitality-uk/eligibility/vitality-uk-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Vitality's own page on 2026-11-10.
synthetic: false
tags:
- Insurance
- United Kingdom
- Health Insurance
- Life Insurance
- Employee Benefits
- Carrier
- Policy Administration
- Underwriting
---
