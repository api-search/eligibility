---
api_specs:
- filename: knownwell-alignment-api-openapi.yml
  format: yaml
  label: Knownwell Alignment API
  slug: knownwell-alignment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-alignment-api-openapi.yml
- filename: knownwell-api-keys-api-openapi.yml
  format: yaml
  label: Knownwell API Keys API
  slug: knownwell-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-api-keys-api-openapi.yml
- filename: knownwell-clients-api-openapi.yml
  format: yaml
  label: Knownwell Clients API
  slug: knownwell-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-clients-api-openapi.yml
- filename: knownwell-documentation-api-openapi.yml
  format: yaml
  label: Knownwell Documentation API
  slug: knownwell-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-documentation-api-openapi.yml
- filename: knownwell-health-api-openapi.yml
  format: yaml
  label: Knownwell Health API
  slug: knownwell-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-health-api-openapi.yml
- filename: knownwell-portfolios-api-openapi.yml
  format: yaml
  label: Knownwell Portfolios API
  slug: knownwell-portfolios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-portfolios-api-openapi.yml
- filename: knownwell-root-api-openapi.yml
  format: yaml
  label: Knownwell Root API
  slug: knownwell-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-root-api-openapi.yml
- filename: knownwell-status-api-openapi.yml
  format: yaml
  label: Knownwell Status API
  slug: knownwell-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-status-api-openapi.yml
- filename: knownwell-streams-api-openapi.yml
  format: yaml
  label: Knownwell Streams API
  slug: knownwell-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-streams-api-openapi.yml
- filename: knownwell-topics-api-openapi.yml
  format: yaml
  label: Knownwell Topics API
  slug: knownwell-topics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/knownwell/openapi/knownwell-topics-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer shall not permit Users to access or use any Service in a U.S.-embargoed country or region or in violation of any U.S. export law or regulation.
  entity_types:
  - text: If an individual accepting this Agreement is accepting on behalf of a company or other legal entity, such individual represents that they have the authority to bind such entity and its affiliates to these terms and conditions
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Highly Sensitive Information not to be processed
    text: use of the Services to transmit, store, or otherwise process “Highly Sensitive Information” is unnecessary for use of the Services
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
name: Knownwell
provenance_date: '2026-11-09'
provider_name: Knownwell
provider_slug: knownwell
slug: knownwell-eligibility
source_date: '2026-11-09'
source_filename: knownwell-eligibility.yml
source_heading: Eligibility
source_page: https://knownwell.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Knownwell\naid: knownwell\nurl: https://knownwell.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer shall not permit Users to access or use any Service in a U.S.-embargoed country or region or in\n    violation of any U.S. export law or regulation.\nentity_types:\n- type: business\n  text: If an individual accepting this Agreement is accepting on behalf of a company or other legal entity, such\n    individual represents that they have the authority to bind such entity and its affiliates to these terms and\n    conditions\nrestricted_uses:\n- summary:\
  \ Highly Sensitive Information not to be processed\n  text: use of the Services to transmit, store, or otherwise process “Highly Sensitive Information” is unnecessary\n    for use of the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/knownwell/eligibility/knownwell-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Knownwell's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commercial Intelligence
- Client Intelligence
- Customer Success
- Revenue Operations
- Professional Services
- Artificial Intelligence
- Analytics
- CRM
- Churn Risk
---
