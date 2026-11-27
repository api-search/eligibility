---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Services and information intended for users of the Site are not for use by children under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Children under 13
    text: Services and information intended for users of the Site are not for use by children under 13 years of age.
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
name: Permiso
provenance_date: '2026-11-10'
provider_name: Permiso
provider_slug: permiso
slug: permiso-eligibility
source_date: '2026-11-10'
source_filename: permiso-eligibility.yml
source_heading: Eligibility
source_page: https://permiso.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Permiso\naid: permiso\nurl: https://permiso.io/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Children under 13\n  text: Services and information intended for users of the Site are not for use by children under 13 years of age.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Services and information intended for users of the Site are not for use by children under 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/permiso/eligibility/permiso-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Permiso's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Identity
- Artificial Intelligence
- Cloud
---
