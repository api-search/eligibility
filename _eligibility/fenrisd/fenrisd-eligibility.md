---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to the Services is limited to use in the United States and its territories.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No FCRA-type consumer eligibility decisions
    text: the Services may not be used in whole or in part as a factor in determining eligibility for credit, insurance, employment or another purpose in connection with which a consumer report may be used under the FCRA.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You acknowledge and understand that the use of the Services may be subject to verification of your credentials in accordance with the Company’s policies and procedures.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Fenris MCP Server
provenance_date: '2026-11-09'
provider_name: Fenris MCP Server
provider_slug: fenrisd
slug: fenrisd-eligibility
source_date: '2026-11-09'
source_filename: fenrisd-eligibility.yml
source_heading: Eligibility
source_page: https://fenrisd.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fenris MCP Server\naid: fenrisd\nurl: https://fenrisd.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to the Services is limited to use in the United States and its territories.\nentity_types: []\nrestricted_uses:\n- summary: No FCRA-type consumer eligibility decisions\n  text: the Services may not be used in whole or in part as a factor in determining eligibility for credit, insurance,\n    employment or another purpose in connection with which a consumer report may be used under the FCRA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: You acknowledge and understand that the use of the Services may be subject to verification of your credentials\n    in accordance with the Company’s policies and procedures.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fenrisd/eligibility/fenrisd-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Fenris MCP Server's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Data
- Artificial Intelligence
---
