---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use restrictions
    text: use the Platform in a manner that violates or attempts to circumvent Applicable Law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Kusari may refuse registration or its initial provision of Services for any reason or no reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kusari
provenance_date: '2026-11-09'
provider_name: Kusari
provider_slug: kusari
slug: kusari-eligibility
source_date: '2026-11-09'
source_filename: kusari-eligibility.yml
source_heading: Eligibility
source_page: https://www.kusari.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kusari\naid: kusari\nurl: https://www.kusari.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use restrictions\n  text: use the Platform in a manner that violates or attempts to circumvent Applicable Law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Kusari may refuse registration or its initial provision of Services for any reason or no reason.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kusari/eligibility/kusari-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Kusari's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Software Supply Chain
- DevOps
- Open Source
---
