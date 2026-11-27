---
api_specs:
- filename: algrow-online-openapi-generated.yml
  format: yaml
  label: Algrow API
  slug: algrow-online-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algrow-online/openapi/_ae-authored/algrow-online-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company does not represent or warrant that the Site or any part thereof is appropriate or available for use in any particular jurisdiction.
  entity_types:
  - text: The "unlimited" pricing is offered on a per-individual basis only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No resale, wholesale or API use of Voice Generation
    text: You may not use the Voice Generation Feature, in whole or in part, directly or indirectly, to operate or supply any service, product, API, application, agency offering
  - summary: Manual use only for Voice Generation
    text: The Voice Generation Feature is intended for manual, interactive use through the Site's user interface only.
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
name: Algrow
provenance_date: '2026-11-09'
provider_name: Algrow
provider_slug: algrow-online
slug: algrow-online-eligibility
source_date: '2026-11-09'
source_filename: algrow-online-eligibility.yml
source_heading: Eligibility
source_page: https://algrow.online/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Algrow\naid: algrow-online\nurl: https://algrow.online/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company does not represent or warrant that the Site or any part thereof is appropriate or available\n    for use in any particular jurisdiction.\nentity_types:\n- type: individual\n  text: The \"unlimited\" pricing is offered on a per-individual basis only.\nrestricted_uses:\n- summary: No resale, wholesale or API use of Voice Generation\n  text: You may not use the Voice Generation Feature, in whole or in part, directly or indirectly, to operate or\n    supply any service,\
  \ product, API, application, agency offering\n- summary: Manual use only for Voice Generation\n  text: The Voice Generation Feature is intended for manual, interactive use through the Site's user interface only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/algrow-online/eligibility/algrow-online-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Algrow's own page on 2026-11-09.
synthetic: false
tags:
- YouTube
- Content Creation
- Artificial Intelligence
- Analytics
- Marketing
---
