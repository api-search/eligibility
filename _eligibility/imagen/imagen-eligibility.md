---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'International Use: No content may be exported to anyone on the United States Treasury Department''s list of Specially Designated Nationals or the U.S. Commerce Department''s Table of Deny Orders.'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No medical advice or diagnostic use of site content
    text: NOTHING ON THE SITE SHOULD BE CONSTRUED AS ADVICE OR A RECOMMENDATION OF ANY DIAGNOSIS OR TREATMENT BY IMAGEN, ANY RADIOLOGISTS AFFILIATED WITH IMAGEN, OR ANY THIRD PARTY, OR SHOULD BE USED FOR DIAGNOSTIC OR TREATMENT PURPOSES.
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
name: Imagen
provenance_date: '2026-11-09'
provider_name: Imagen
provider_slug: imagen
slug: imagen-eligibility
source_date: '2026-11-09'
source_filename: imagen-eligibility.yml
source_heading: Eligibility
source_page: https://imagen.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imagen\naid: imagen\nurl: https://imagen.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'International Use: No content may be exported to anyone on the United States Treasury Department''s list\n    of Specially Designated Nationals or the U.S. Commerce Department''s Table of Deny Orders.'\nentity_types: []\nrestricted_uses:\n- summary: No medical advice or diagnostic use of site content\n  text: NOTHING ON THE SITE SHOULD BE CONSTRUED AS ADVICE OR A RECOMMENDATION OF ANY DIAGNOSIS OR TREATMENT BY IMAGEN,\n    ANY RADIOLOGISTS AFFILIATED WITH IMAGEN, OR ANY THIRD\
  \ PARTY, OR SHOULD BE USED FOR DIAGNOSTIC OR TREATMENT PURPOSES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/imagen/eligibility/imagen-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Imagen's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Frontier Tech
- Healthcare
- Radiology
- Medical Imaging
- Teleradiology
- Artificial Intelligence
- Diagnostics
---
