---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not export to countries requiring export license, including Cuba, Libya, North Korea, Iran, Iraq, or Rwanda
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No nuclear, chemical, biological or missile proliferation use
    text: use the Service in support of any nuclear proliferation, chemical weapon, biological weapon or missile proliferation activity
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
name: Arrikto
provenance_date: '2026-11-09'
provider_name: Arrikto
provider_slug: arrikto
slug: arrikto-eligibility
source_date: '2026-11-09'
source_filename: arrikto-eligibility.yml
source_heading: Eligibility
source_page: https://www.arrikto.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arrikto\naid: arrikto\nurl: https://www.arrikto.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not export to countries requiring export license, including Cuba, Libya, North Korea, Iran,\n    Iraq, or Rwanda\nentity_types: []\nrestricted_uses:\n- summary: No nuclear, chemical, biological or missile proliferation use\n  text: use the Service in support of any nuclear proliferation, chemical weapon, biological weapon or missile proliferation\n    activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arrikto/eligibility/arrikto-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Arrikto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MLOps
- Kubernetes
- Artificial Intelligence
- Data Management
---
