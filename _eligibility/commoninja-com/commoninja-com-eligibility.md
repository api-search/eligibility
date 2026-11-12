---
api_specs:
- filename: commoninja-com-openapi-generated.yml
  format: yaml
  label: Common Ninja Platform API
  slug: commoninja-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/commoninja-com/openapi/_ae-authored/commoninja-com-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer may access and use the Platform solely for Customer’s own internal business operations
    type: business
  - text: 'The Platform may only be used by individuals who: (i) can form legally binding contracts under applicable law, and (ii) are authorized to use the Platform pursuant to a Customer’s procedures and policies (if any).'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Native Payments prohibited purposes
    text: The use of Native Payments for any unlawful or prohibited purposes is strictly forbidden.
  - summary: No pornographic content sales via Native Payments
    text: The sale or distribution of pornographic content or materials;
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
name: Common Ninja
provenance_date: '2026-11-09'
provider_name: Common Ninja
provider_slug: commoninja-com
slug: commoninja-com-eligibility
source_date: '2026-11-09'
source_filename: commoninja-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.commoninja.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Common Ninja\naid: commoninja-com\nurl: https://www.commoninja.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer may access and use the Platform solely for Customer’s own internal business operations\n- type: individual\n  text: 'The Platform may only be used by individuals who: (i) can form legally binding contracts under applicable\n    law, and (ii) are authorized to use the Platform pursuant to a Customer’s procedures and policies (if any).'\nrestricted_uses:\n- summary: Native Payments prohibited purposes\n  text:\
  \ The use of Native Payments for any unlawful or prohibited purposes is strictly forbidden.\n- summary: No pornographic content sales via Native Payments\n  text: The sale or distribution of pornographic content or materials;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/commoninja-com/eligibility/commoninja-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Common Ninja's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Widgets
- No-Code
- Website Builder
- White Label
- Webhooks
- E-Commerce
- Developer Platform
---
