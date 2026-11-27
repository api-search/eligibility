---
api_specs:
- filename: maplith-com-openapi-generated.yml
  format: yaml
  label: maplith-com API
  slug: maplith-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/maplith-com/openapi/_ae-authored/maplith-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Maplith is built for businesses.
    type: business
  - text: It is not offered to consumers, and by using it you confirm that you do not act as a consumer.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Hosted agent in uncontrolled repositories
    text: Do not use the hosted agent in repositories you do not control.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By creating a workspace you confirm that you act on behalf of an organisation and have the authority to bind it to these terms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: maplith-com
provenance_date: '2026-11-10'
provider_name: maplith-com
provider_slug: maplith-com
slug: maplith-com-eligibility
source_date: '2026-11-10'
source_filename: maplith-com-eligibility.yml
source_heading: Eligibility
source_page: https://maplith.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: maplith-com\naid: maplith-com\nurl: https://maplith.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Maplith is built for businesses.\n- type: other\n  text: It is not offered to consumers, and by using it you confirm that you do not act as a consumer.\nrestricted_uses:\n- summary: Hosted agent in uncontrolled repositories\n  text: Do not use the hosted agent in repositories you do not control.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By creating a workspace you confirm that you act on behalf\
  \ of an organisation and have the authority to\n    bind it to these terms.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/maplith-com/eligibility/maplith-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from maplith-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Data Integration
- Knowledge Graph
- Platform
---
