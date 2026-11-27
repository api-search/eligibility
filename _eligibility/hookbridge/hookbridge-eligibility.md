---
api_specs:
- filename: hookbridge-api-openapi.yml
  format: yaml
  label: HookBridge API API
  slug: hookbridge-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hookbridge/openapi/_original/hookbridge-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have legal capacity to enter into these Terms.
    type: individual
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and have legal capacity to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Export control and sanctions
    text: You may not use the Services in violation of applicable export control or sanctions laws.
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
name: Hookbridge
provenance_date: '2026-11-09'
provider_name: Hookbridge
provider_slug: hookbridge
slug: hookbridge-eligibility
source_date: '2026-11-09'
source_filename: hookbridge-eligibility.yml
source_heading: Eligibility
source_page: https://www.hookbridge.io/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hookbridge\naid: hookbridge\nurl: https://www.hookbridge.io/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have legal capacity to enter into these Terms.\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization.\nrestricted_uses:\n- summary: Export control and sanctions\n  text: You may not use the Services in violation of applicable export control or sanctions laws.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have legal capacity to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/hookbridge/eligibility/hookbridge-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hookbridge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Webhook
- Software-as-a-Service
- Integration
---
