---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not access or use the Services if Customer or any Authorized Users are located in any jurisdiction in which the provision of the Services ... is prohibited under U.S. or other applicable laws
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
name: Chkk
provenance_date: '2026-11-09'
provider_name: Chkk
provider_slug: chkk
slug: chkk-eligibility
source_date: '2026-11-09'
source_filename: chkk-eligibility.yml
source_heading: Eligibility
source_page: https://docs.chkk.io/security/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chkk\naid: chkk\nurl: https://docs.chkk.io/security/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not access or use the Services if Customer or any Authorized Users are located in any jurisdiction\n    in which the provision of the Services ... is prohibited under U.S. or other applicable laws\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chkk/eligibility/chkk-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Chkk's own page on 2026-11-09.
synthetic: false
tags:
- Lifecycle Management
- Kubernetes
- Cloud-Native
- Enterprise Software
---
