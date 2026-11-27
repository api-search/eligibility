---
api_specs:
- filename: quickwork-embedded-api-openapi.yml
  format: yaml
  label: Quickwork Embedded API
  slug: quickwork-embedded-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quickwork/openapi/quickwork-embedded-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer shall include any person, firm, company, or entity that is a user or purchaser of Products and Services offered and provided by Quickwork
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive product development
    text: Access the Platform and/or the Website in order to build a similar or competitive product or service
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
name: Quickwork
provenance_date: '2026-11-10'
provider_name: Quickwork
provider_slug: quickwork
slug: quickwork-eligibility
source_date: '2026-11-10'
source_filename: quickwork-eligibility.yml
source_heading: Eligibility
source_page: https://www.quickwork.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quickwork\naid: quickwork\nurl: https://www.quickwork.co/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Customer shall include any person, firm, company, or entity that is a user or purchaser of Products and\n    Services offered and provided by Quickwork\nrestricted_uses:\n- summary: Competitive product development\n  text: Access the Platform and/or the Website in order to build a similar or competitive product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quickwork/eligibility/quickwork-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Quickwork's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- Automation
- Workflows
- API Platform
- Enterprise
---
