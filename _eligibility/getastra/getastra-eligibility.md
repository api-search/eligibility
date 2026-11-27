---
api_specs:
- filename: getastra-openapi-generated.yml
  format: yaml
  label: Astra Pentest API
  slug: getastra-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getastra/openapi/_ae-authored/getastra-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Platform and the Service are controlled and offered by Us from India and the USA. The Company makes no representations that the Platform or the Service are appropriate or available for use in other locations.
  entity_types:
  - text: Only individuals who are eighteen(18) years of age or older may use the Platform and avail Services.
    type: individual
  - text: The Platform and Services can be accessed and used by those individuals or business entities, including sole proprietorship firms, companies and partnerships, which can form legally binding contracts under the applicable law.
    type: business
  minimum_age:
    text: Only individuals who are eighteen(18) years of age or older may use the Platform and avail Services.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You will not use any of the Services for any illegal or unauthorized purpose.
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
name: Astra Pentest
provenance_date: '2026-11-09'
provider_name: Astra Pentest
provider_slug: getastra
slug: getastra-eligibility
source_date: '2026-11-09'
source_filename: getastra-eligibility.yml
source_heading: Eligibility
source_page: https://www.getastra.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Astra Pentest\naid: getastra\nurl: https://www.getastra.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Platform and the Service are controlled and offered by Us from India and the USA. The Company makes\n    no representations that the Platform or the Service are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: Only individuals who are eighteen(18) years of age or older may use the Platform and avail Services.\n- type: business\n  text: The Platform and Services can be accessed and used by those individuals or business\
  \ entities, including\n    sole proprietorship firms, companies and partnerships, which can form legally binding contracts under the applicable\n    law.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You will not use any of the Services for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Only individuals who are eighteen(18) years of age or older may use the Platform and avail Services.\n"
source_yaml_url: https://artifacts.apis.io/getastra/eligibility/getastra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Astra Pentest's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Penetration Testing
- Cloud
---
