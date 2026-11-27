---
api_specs:
- filename: withvector-com-openapi-generated.yml
  format: yaml
  label: Vector API
  slug: withvector-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/withvector-com/openapi/_ae-authored/withvector-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years of age to use our Site.
    value: '18'
  restricted_uses:
  - summary: Export control restrictions
    text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any country subject to a U.S. government embargo or other restriction
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
name: Vector
provenance_date: '2026-11-10'
provider_name: Vector
provider_slug: withvector-com
slug: withvector-com-eligibility
source_date: '2026-11-10'
source_filename: withvector-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.withvector.com/terms-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vector\naid: withvector-com\nurl: https://www.withvector.com/terms-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control restrictions\n  text: You represent, warrant and covenant that you are not (a) located in, or a resident or a national of, any\n    country subject to a U.S. government embargo or other restriction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/withvector-com/eligibility/withvector-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Vector's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Platform
- Enterprise
---
