---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are an individual using the Services for your own purposes: (1) all references to “Customer” are to you'
    type: individual
  - text: If you are using the Services on behalf of an entity or organization that you represent
    type: business
  minimum_age:
    text: you represent and warrant that you are at least 18 years of age, or have otherwise reached the age of “majority” where you reside
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties and export controls
    text: not directly or indirectly export, re-export or otherwise deliver Services to a Sanctions Target
  - summary: Protected Information
    text: Customer shall not use the Services to process any Protected Information
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
name: Superconductive
provenance_date: '2026-11-10'
provider_name: Superconductive
provider_slug: superconductive
slug: superconductive-eligibility
source_date: '2026-11-10'
source_filename: superconductive-eligibility.yml
source_heading: Eligibility
source_page: https://greatexpectations.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Superconductive\naid: superconductive\nurl: https://greatexpectations.io/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'If you are an individual using the Services for your own purposes: (1) all references to “Customer” are\n    to you'\n- type: business\n  text: If you are using the Services on behalf of an entity or organization that you represent\nrestricted_uses:\n- summary: Sanctioned parties and export controls\n  text: not directly or indirectly export, re-export or otherwise deliver Services to a Sanctions\
  \ Target\n- summary: Protected Information\n  text: Customer shall not use the Services to process any Protected Information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least 18 years of age, or have otherwise reached the age of “majority”\n    where you reside\n"
source_yaml_url: https://artifacts.apis.io/superconductive/eligibility/superconductive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Superconductive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Data Quality
- Data Validation
- Data Testing
- Open Source
- Python
---
