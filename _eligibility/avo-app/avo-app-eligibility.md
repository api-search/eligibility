---
api_specs:
- filename: avo-app-openapi-generated.yml
  format: yaml
  label: Avo API
  slug: avo-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avo-app/openapi/_ae-authored/avo-app-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Avo Platform is an application for businesses to define their analytics events
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal information processing
    text: the Services are not intended to be used for the processing of any information that identifies, relates to, describes
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
name: Avo
provenance_date: '2026-11-09'
provider_name: Avo
provider_slug: avo-app
slug: avo-app-eligibility
source_date: '2026-11-09'
source_filename: avo-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.avo.app/l/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avo\naid: avo-app\nurl: https://www.avo.app/l/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Avo Platform is an application for businesses to define their analytics events\nrestricted_uses:\n- summary: No personal information processing\n  text: the Services are not intended to be used for the processing of any information that identifies, relates\n    to, describes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/avo-app/eligibility/avo-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Avo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Governance
- Analytics
- Artificial Intelligence
- Software-as-a-Service
---
