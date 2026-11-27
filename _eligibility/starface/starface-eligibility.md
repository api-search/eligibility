---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Contracts concluded between STARFACE GmbH (in the following, “STARFACE”) and an entrepreneur as defined in Section 14 of the German Civil Code
    type: business
  - text: Contracts between STARFACE and a consumer (as defined in Section 13 of the German Civil Code) are subject to the corresponding statutory provisions.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Cloud access requires certified partner status
    text: As a prerequisite for doing so, the partner must first be certified as a STARFACE Certified Partner.
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
name: STARFACE
provenance_date: '2026-11-10'
provider_name: STARFACE
provider_slug: starface
slug: starface-eligibility
source_date: '2026-11-10'
source_filename: starface-eligibility.yml
source_heading: Eligibility
source_page: https://starface.com/en/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: STARFACE\naid: starface\nurl: https://starface.com/en/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Contracts concluded between STARFACE GmbH (in the following, “STARFACE”) and an entrepreneur as defined\n    in Section 14 of the German Civil Code\n- type: individual\n  text: Contracts between STARFACE and a consumer (as defined in Section 13 of the German Civil Code) are subject\n    to the corresponding statutory provisions.\nrestricted_uses:\n- summary: Cloud access requires certified partner status\n  text: As\
  \ a prerequisite for doing so, the partner must first be certified as a STARFACE Certified Partner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/starface/eligibility/starface-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from STARFACE's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Unified Communications
- VoIP
---
