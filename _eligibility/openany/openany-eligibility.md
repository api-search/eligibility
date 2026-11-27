---
api_specs:
- filename: openany-openapi-generated.yml
  format: yaml
  label: OpenAny API
  slug: openany-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openany/openapi/_ae-authored/openany-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use the service only if you can enter into these terms and have authority to act for any organization or account you connect.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive activity
    text: Do not use OpenAny for unlawful activity, unauthorized access, fraud, infringement, evading access restrictions or compromising the service.
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
name: OpenAny
provenance_date: '2026-11-10'
provider_name: OpenAny
provider_slug: openany
slug: openany-eligibility
source_date: '2026-11-10'
source_filename: openany-eligibility.yml
source_heading: Eligibility
source_page: https://openany.si/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenAny\naid: openany\nurl: https://openany.si/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Use the service only if you can enter into these terms and have authority to act for any organization or\n    account you connect.\nrestricted_uses:\n- summary: Unlawful or abusive activity\n  text: Do not use OpenAny for unlawful activity, unauthorized access, fraud, infringement, evading access restrictions\n    or compromising the service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openany/eligibility/openany-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from OpenAny's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Agents
- Models
---
