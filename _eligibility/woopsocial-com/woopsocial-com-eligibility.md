---
api_specs:
- filename: woopsocial-com-openapi-openapi.yml
  format: yaml
  label: woopsocial-com Openapi API
  slug: woopsocial-com-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woopsocial-com/openapi/_original/woopsocial-com-openapi-openapi.yml
- filename: woopsocial-com-out-openapi-openapi.yml
  format: yaml
  label: woopsocial-com Out.Openapi API
  slug: woopsocial-com-out-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woopsocial-com/openapi/_original/woopsocial-com-out-openapi-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: To be at least 13 years old (legal requirements!)
    value: '13'
  restricted_uses:
  - summary: Adult and illegal content
    text: 'Zero tolerance: We do not allow adult (18+) content or illegal content to be promoted through WoopSocial in any form.'
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
name: woopsocial-com
provenance_date: '2026-11-10'
provider_name: woopsocial-com
provider_slug: woopsocial-com
slug: woopsocial-com-eligibility
source_date: '2026-11-10'
source_filename: woopsocial-com-eligibility.yml
source_heading: Eligibility
source_page: https://woopsocial.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: woopsocial-com\naid: woopsocial-com\nurl: https://woopsocial.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Adult and illegal content\n  text: 'Zero tolerance: We do not allow adult (18+) content or illegal content to be promoted through WoopSocial\n    in any form.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To be at least 13 years old (legal requirements!)\n"
source_yaml_url: https://artifacts.apis.io/woopsocial-com/eligibility/woopsocial-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from woopsocial-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- MCP
- AI Agents
---
