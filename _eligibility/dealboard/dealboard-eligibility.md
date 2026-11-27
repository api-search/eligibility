---
api_specs:
- filename: dealboard-deals-api-openapi.yml
  format: yaml
  label: Dealboard Deals API
  slug: dealboard-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-deals-api-openapi.yml
- filename: dealboard-reports-api-openapi.yml
  format: yaml
  label: Dealboard Reports API
  slug: dealboard-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-reports-api-openapi.yml
- filename: dealboard-templates-api-openapi.yml
  format: yaml
  label: Dealboard Templates API
  slug: dealboard-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-templates-api-openapi.yml
- filename: dealboard-auth-api-openapi.yml
  format: yaml
  label: Dealboard Auth API
  slug: dealboard-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-auth-api-openapi.yml
- filename: dealboard-boards-api-openapi.yml
  format: yaml
  label: Dealboard Boards API
  slug: dealboard-boards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-boards-api-openapi.yml
- filename: dealboard-dealboard-api-api-openapi.yml
  format: yaml
  label: Dealboard Dealboard API
  slug: dealboard-dealboard-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-dealboard-api-api-openapi.yml
- filename: dealboard-leads-api-openapi.yml
  format: yaml
  label: Dealboard Leads API
  slug: dealboard-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-leads-api-openapi.yml
- filename: dealboard-match-api-openapi.yml
  format: yaml
  label: Dealboard Match API
  slug: dealboard-match-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-match-api-openapi.yml
- filename: dealboard-notes-api-openapi.yml
  format: yaml
  label: Dealboard Notes API
  slug: dealboard-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-notes-api-openapi.yml
- filename: dealboard-webhooks-api-openapi.yml
  format: yaml
  label: Dealboard Webhooks API
  slug: dealboard-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealboard/openapi/dealboard-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per natural person; account sharing is not permitted.
    type: individual
  - text: If you're entering into them on behalf of a company, you represent that you have authority to bind that company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctions and export controls
    text: Use the Service to evade sanctions, export controls, or applicable law.
  - summary: No spam
    text: Send unsolicited communications via the Service or use the lead-capture features for spam.
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
name: Dealboard
provenance_date: '2026-11-09'
provider_name: Dealboard
provider_slug: dealboard
slug: dealboard-eligibility
source_date: '2026-11-09'
source_filename: dealboard-eligibility.yml
source_heading: Eligibility
source_page: https://getdealboard.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dealboard\naid: dealboard\nurl: https://getdealboard.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per natural person; account sharing is not permitted.\n- type: business\n  text: If you're entering into them on behalf of a company, you represent that you have authority to bind that\n    company.\nrestricted_uses:\n- summary: Sanctions and export controls\n  text: Use the Service to evade sanctions, export controls, or applicable law.\n- summary: No spam\n  text: Send unsolicited communications via the Service\
  \ or use the lead-capture features for spam.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dealboard/eligibility/dealboard-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Dealboard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Sales
- Artificial Intelligence
- Integration
---
