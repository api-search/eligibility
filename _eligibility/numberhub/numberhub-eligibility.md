---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: Prohibited by applicable law
    text: You must not use the Service where doing so is prohibited by the laws applicable to you.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: While the Service does not require identity documents to browse or transact for ordinary, low-value verification use, we operate risk controls.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: NumberHub
provenance_date: '2026-11-10'
provider_name: NumberHub
provider_slug: numberhub
slug: numberhub-eligibility
source_date: '2026-11-10'
source_filename: numberhub-eligibility.yml
source_heading: Eligibility
source_page: https://numberhub.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NumberHub\naid: numberhub\nurl: https://numberhub.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a contract.\nrestricted_uses:\n- summary: Prohibited by applicable law\n  text: You must not use the Service where doing so is prohibited by the laws applicable to you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: While the Service does not require identity documents to browse or transact for ordinary, low-value verification\n   \
  \ use, we operate risk controls.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/numberhub/eligibility/numberhub-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from NumberHub's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- SMS Verification
- eSIM
- Residential Proxies
---
