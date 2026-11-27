---
api_specs:
- filename: shipsy-website-ai-api-openapi.yml
  format: yaml
  label: Shipsy Website AI API
  slug: shipsy-website-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shipsy/openapi/shipsy-website-ai-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of an organisation, you represent that you have the authority to bind that organisation.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competing product
    text: Use the Platform to build a competing product or service
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
name: Shipsy
provenance_date: '2026-11-10'
provider_name: Shipsy
provider_slug: shipsy
slug: shipsy-eligibility
source_date: '2026-11-10'
source_filename: shipsy-eligibility.yml
source_heading: Eligibility
source_page: https://www.shipsy.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shipsy\naid: shipsy\nurl: https://www.shipsy.ai/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of an organisation, you represent that you have the authority\n    to bind that organisation.\nrestricted_uses:\n- summary: No competing product\n  text: Use the Platform to build a competing product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shipsy/eligibility/shipsy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Shipsy's own page on 2026-11-10.
synthetic: false
tags:
- Logistics
- Artificial Intelligence
- Transportation
- Warehouse
- Software-as-a-Service
- Company
---
