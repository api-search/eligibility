---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No clinical use of beta services
    text: You agree that You will not use the Beta Services for clinical patient treatment purposes.
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
name: 4DMedical
provenance_date: '2026-11-09'
provider_name: 4DMedical
provider_slug: 4dmedical
slug: 4dmedical-eligibility
source_date: '2026-11-09'
source_filename: 4dmedical-eligibility.yml
source_heading: Eligibility
source_page: https://4dmedical.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 4DMedical\naid: 4dmedical\nurl: https://4dmedical.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: No clinical use of beta services\n  text: You agree that You will not use the Beta Services for clinical patient treatment purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/4dmedical/eligibility/4dmedical-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from 4DMedical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Medical Imaging
- Lung Function
- Respiratory
- Software
- Australia
---
