---
api_specs:
- filename: spekit-searches-api-openapi.yml
  format: yaml
  label: Spekit Searches API
  slug: spekit-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spekit/openapi/spekit-searches-api-openapi.yml
- filename: spekit-spek-reactions-api-openapi.yml
  format: yaml
  label: Spekit Spek Reactions API
  slug: spekit-spek-reactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spekit/openapi/spekit-spek-reactions-api-openapi.yml
- filename: spekit-spek-views-api-openapi.yml
  format: yaml
  label: Spekit Spek Views API
  slug: spekit-spek-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spekit/openapi/spekit-spek-views-api-openapi.yml
- filename: spekit-user-activities-api-openapi.yml
  format: yaml
  label: Spekit User Activities API
  slug: spekit-user-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spekit/openapi/spekit-user-activities-api-openapi.yml
- filename: spekit-users-api-openapi.yml
  format: yaml
  label: Spekit Users API
  slug: spekit-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spekit/openapi/spekit-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: agree to this Master Services Agreement on behalf of the customer indicated on the Order Form (if applicable) or the organization, business, or other legal entity for which you act
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto
  - source: https://www.spekit.com/legal/spekit-acceptable-use-policy
    summary: Unlawful or fraudulent use
    text: Use the Service for any purpose that is fraudulent or otherwise tortious or unlawful.
  - source: https://www.spekit.com/legal/spekit-acceptable-use-policy
    summary: Transmitting sensitive personal data
    text: Transmit highly sensitive personal information of an individual in a manner that can be associated with the individual
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
name: Spekit
provenance_date: '2026-11-10'
provider_name: Spekit
provider_slug: spekit
slug: spekit-eligibility
source_date: '2026-11-10'
source_filename: spekit-eligibility.yml
source_heading: Eligibility
source_page: https://www.spekit.com/legal/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spekit\naid: spekit\nurl: https://www.spekit.com/legal/msa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.spekit.com/legal/msa\n  - https://www.spekit.com/legal/spekit-acceptable-use-policy\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: agree to this Master Services Agreement on behalf of the customer indicated on the Order Form (if applicable)\n    or the organization, business, or other legal entity for which you act\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export\
  \ or re-export of the Services,\n    Software or anything related thereto\n- summary: Unlawful or fraudulent use\n  text: Use the Service for any purpose that is fraudulent or otherwise tortious or unlawful.\n  source: https://www.spekit.com/legal/spekit-acceptable-use-policy\n- summary: Transmitting sensitive personal data\n  text: Transmit highly sensitive personal information of an individual in a manner that can be associated with\n    the individual\n  source: https://www.spekit.com/legal/spekit-acceptable-use-policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spekit/eligibility/spekit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Spekit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Sales Enablement
- Revenue Enablement
- Digital Adoption
- Knowledge Management
- MCP
- Artificial Intelligence
- Analytics
- Sales
- Content Management
- Agents
- OAuth
- Authentication
---
