---
api_specs:
- filename: cms-energy-authorizations-api-openapi.yml
  format: yaml
  label: CMS Energy Authorizations API
  slug: cms-energy-authorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-authorizations-api-openapi.yml
- filename: cms-energy-bills-api-openapi.yml
  format: yaml
  label: CMS Energy Bills API
  slug: cms-energy-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-bills-api-openapi.yml
- filename: cms-energy-greenbutton-api-openapi.yml
  format: yaml
  label: CMS Energy GreenButton API
  slug: cms-energy-greenbutton-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-greenbutton-api-openapi.yml
- filename: cms-energy-intervals-api-openapi.yml
  format: yaml
  label: CMS Energy Intervals API
  slug: cms-energy-intervals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-intervals-api-openapi.yml
- filename: cms-energy-meters-api-openapi.yml
  format: yaml
  label: CMS Energy Meters API
  slug: cms-energy-meters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-meters-api-openapi.yml
- filename: cms-energy-outage-map-api-openapi.yml
  format: yaml
  label: Consumers Energy Outage Map ArcGIS REST API
  slug: cms-energy-outage-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-outage-map-api-openapi.yml
- filename: cms-energy-catalog-api-openapi.yml
  format: yaml
  label: CMS Energy Catalog API
  slug: cms-energy-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-catalog-api-openapi.yml
- filename: cms-energy-service-dashboard-api-openapi.yml
  format: yaml
  label: CMS Energy Service Dashboard API
  slug: cms-energy-service-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-service-dashboard-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraudulent or unauthorized use of customer data
    text: engage in fraudulent, misleading, or unauthorized use of customer data or intellectual property
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
name: CMS Energy
provenance_date: '2026-11-09'
provider_name: CMS Energy
provider_slug: cms-energy
slug: cms-energy-eligibility
source_date: '2026-11-09'
source_filename: cms-energy-eligibility.yml
source_heading: Eligibility
source_page: https://greenbutton.consumersenergy.com/third-party/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CMS Energy\naid: cms-energy\nurl: https://greenbutton.consumersenergy.com/third-party/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent or unauthorized use of customer data\n  text: engage in fraudulent, misleading, or unauthorized use of customer data or intellectual property\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cms-energy/eligibility/cms-energy-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CMS Energy's own page on 2026-11-09.
synthetic: false
tags:
- Electric
- Energy
- Green Button
- Michigan
- Natural Gas
- Utility
- Fortune 500
---
