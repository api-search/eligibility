---
api_specs:
- filename: aquant-agent-data-api-openapi.yml
  format: yaml
  label: Aquant Agent Data API
  slug: aquant-agent-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-agent-data-api-openapi.yml
- filename: aquant-asset-location-api-openapi.yml
  format: yaml
  label: Aquant Asset Location API
  slug: aquant-asset-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-asset-location-api-openapi.yml
- filename: aquant-health-api-openapi.yml
  format: yaml
  label: Aquant Health API
  slug: aquant-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-health-api-openapi.yml
- filename: aquant-next-symptom-api-openapi.yml
  format: yaml
  label: Aquant Next Symptom API
  slug: aquant-next-symptom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-next-symptom-api-openapi.yml
- filename: aquant-observation-existence-api-openapi.yml
  format: yaml
  label: Aquant Observation Existence API
  slug: aquant-observation-existence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-observation-existence-api-openapi.yml
- filename: aquant-part-catalog-lookup-api-openapi.yml
  format: yaml
  label: Aquant Part Catalog Lookup API
  slug: aquant-part-catalog-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-part-catalog-lookup-api-openapi.yml
- filename: aquant-part-info-api-openapi.yml
  format: yaml
  label: Aquant Part Info API
  slug: aquant-part-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-part-info-api-openapi.yml
- filename: aquant-part-sources-api-openapi.yml
  format: yaml
  label: Aquant Part Sources API
  slug: aquant-part-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-part-sources-api-openapi.yml
- filename: aquant-preventive-maintenance-check-list-api-openapi.yml
  format: yaml
  label: Aquant Preventive Maintenance Check List API
  slug: aquant-preventive-maintenance-check-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-preventive-maintenance-check-list-api-openapi.yml
- filename: aquant-summary-report-api-openapi.yml
  format: yaml
  label: Aquant Summary Report API
  slug: aquant-summary-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-summary-report-api-openapi.yml
- filename: aquant-technician-proximity-api-openapi.yml
  format: yaml
  label: Aquant Technician Proximity API
  slug: aquant-technician-proximity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aquant/openapi/aquant-technician-proximity-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organization, you are agreeing to the Agreement on behalf of that organization
    type: business
  minimum_age:
    text: null
    value: null
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
name: Aquant
provenance_date: '2026-11-09'
provider_name: Aquant
provider_slug: aquant
slug: aquant-eligibility
source_date: '2026-11-09'
source_filename: aquant-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/687529371c5de2d8428c0a4d/688ce744542f10274811b354_Terms%20of%20Service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aquant\naid: aquant\nurl: https://cdn.prod.website-files.com/687529371c5de2d8428c0a4d/688ce744542f10274811b354_Terms%20of%20Service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you are agreeing to the Agreement on behalf\n    of that organization\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aquant/eligibility/aquant-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Aquant's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Field Service Management
- Service Management
- Manufacturing
- Medical Devices
- Industrial Equipment
- Knowledge Management
- Voice AI
- MCP
- Predictive Maintenance
---
