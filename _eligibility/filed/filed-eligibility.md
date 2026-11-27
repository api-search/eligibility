---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representation that the Content is appropriate or available for use in locations outside of United States, and accessing the Service is prohibited from territories where such Content is illegal.
  entity_types:
  - text: The Service is provided only for your internal use in connection with your lawful business activities.
    type: business
  minimum_age:
    text: you are of legal age to form a binding contract.
    value: null
  restricted_uses:
  - summary: Export restriction
    text: Customer may not remove or export from the United States or allow the export or re-export of Filed.
  - summary: Prohibited content and conduct
    text: 'you shall not (and shall not permit any third party to) either (a) take any action or (b) post any content on or through the Service, that: • infringes any intellectual property or other proprietary right of any other person or entity'
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
name: Filed
provenance_date: '2026-11-09'
provider_name: Filed
provider_slug: filed
slug: filed-eligibility
source_date: '2026-11-09'
source_filename: filed-eligibility.yml
source_heading: Eligibility
source_page: https://www.filed.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Filed\naid: filed\nurl: https://www.filed.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representation that the Content is appropriate or available for use in locations outside\n    of United States, and accessing the Service is prohibited from territories where such Content is illegal.\nentity_types:\n- type: business\n  text: The Service is provided only for your internal use in connection with your lawful business activities.\nrestricted_uses:\n- summary: Export restriction\n  text: Customer may not remove or export from the United States\
  \ or allow the export or re-export of Filed.\n- summary: Prohibited content and conduct\n  text: 'you shall not (and shall not permit any third party to) either (a) take any action or (b) post any content\n    on or through the Service, that: • infringes any intellectual property or other proprietary right of any other\n    person or entity'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/filed/eligibility/filed-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Filed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tax
- Accounting
- Artificial Intelligence
- Document Processing
- GraphQL
- Compliance
- Enterprise
---
