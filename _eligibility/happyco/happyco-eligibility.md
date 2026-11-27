---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are authorized to register and access certain features of the Website, Services, Apps and/or Related Software on behalf of your company and organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors
    text: You may not access the Services, Apps, and/or Related Software if you are a competitor of HappyCo, except with HappyCo’s prior written consent.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: HappyCo will have the sole discretion to approve or decline an Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HappyCo
provenance_date: '2026-11-09'
provider_name: HappyCo
provider_slug: happyco
slug: happyco-eligibility
source_date: '2026-11-09'
source_filename: happyco-eligibility.yml
source_heading: Eligibility
source_page: https://happy.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HappyCo\naid: happyco\nurl: https://happy.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you are authorized to register and access certain features of the Website, Services, Apps and/or Related\n    Software on behalf of your company and organization\nrestricted_uses:\n- summary: Competitors\n  text: You may not access the Services, Apps, and/or Related Software if you are a competitor of HappyCo, except\n    with HappyCo’s prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n \
  \ text: HappyCo will have the sole discretion to approve or decline an Account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/happyco/eligibility/happyco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from HappyCo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Property Management
- Inspection
- Maintenance
- Multifamily
- gRPC
---
