---
api_specs:
- filename: sap-hana-alerts-api-openapi.yml
  format: yaml
  label: SAP HANA Alerts API
  slug: sap-hana-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap-hana/openapi/sap-hana-alerts-api-openapi.yml
- filename: sap-hana-instance-mappings-api-openapi.yml
  format: yaml
  label: SAP HANA Instance Mappings API
  slug: sap-hana-instance-mappings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap-hana/openapi/sap-hana-instance-mappings-api-openapi.yml
- filename: sap-hana-instances-api-openapi.yml
  format: yaml
  label: SAP HANA Instances API
  slug: sap-hana-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap-hana/openapi/sap-hana-instances-api-openapi.yml
- filename: sap-hana-metering-api-openapi.yml
  format: yaml
  label: SAP HANA Metering API
  slug: sap-hana-metering-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap-hana/openapi/sap-hana-metering-api-openapi.yml
- filename: sap-hana-metrics-api-openapi.yml
  format: yaml
  label: SAP HANA Metrics API
  slug: sap-hana-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sap-hana/openapi/sap-hana-metrics-api-openapi.yml
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
  - summary: Export control and sanctions
    text: SAP software products and services are subject to the export control and sanctions laws of various countries, including Germany and the United States, as well as the European Union.
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
name: SAP HANA
provenance_date: '2026-11-10'
provider_name: SAP HANA
provider_slug: sap-hana
slug: sap-hana-eligibility
source_date: '2026-11-10'
source_filename: sap-hana-eligibility.yml
source_heading: Eligibility
source_page: https://www.sap.com/about/trust-center/agreements.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SAP HANA\naid: sap-hana\nurl: https://www.sap.com/about/trust-center/agreements.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control and sanctions\n  text: SAP software products and services are subject to the export control and sanctions laws of various countries,\n    including Germany and the United States, as well as the European Union.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sap-hana/eligibility/sap-hana-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from SAP HANA's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Cloud
- Database
- Enterprise
- In-Memory
---
