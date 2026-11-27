---
api_specs:
- filename: bigid-authentication-api-openapi.yml
  format: yaml
  label: BigID Authentication API
  slug: bigid-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-authentication-api-openapi.yml
- filename: bigid-data-sources-api-openapi.yml
  format: yaml
  label: BigID Data Sources API
  slug: bigid-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-data-sources-api-openapi.yml
- filename: bigid-scans-api-openapi.yml
  format: yaml
  label: BigID Scans API
  slug: bigid-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-scans-api-openapi.yml
- filename: bigid-dsar-api-openapi.yml
  format: yaml
  label: BigID DSAR API
  slug: bigid-dsar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-dsar-api-openapi.yml
- filename: bigid-actionable-insights-api-openapi.yml
  format: yaml
  label: BigID Actionable Insights API
  slug: bigid-actionable-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-actionable-insights-api-openapi.yml
- filename: bigid-catalog-api-openapi.yml
  format: yaml
  label: BigID Catalog API
  slug: bigid-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-catalog-api-openapi.yml
- filename: bigid-clusters-api-openapi.yml
  format: yaml
  label: BigID Clusters API
  slug: bigid-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-clusters-api-openapi.yml
- filename: bigid-connector-templates-api-openapi.yml
  format: yaml
  label: BigID Connector Templates API
  slug: bigid-connector-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-connector-templates-api-openapi.yml
- filename: bigid-metadata-export-api-openapi.yml
  format: yaml
  label: BigID Metadata Export API
  slug: bigid-metadata-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-metadata-export-api-openapi.yml
- filename: bigid-scan-profiles-api-openapi.yml
  format: yaml
  label: BigID Scan Profiles API
  slug: bigid-scan-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigid/openapi/bigid-scan-profiles-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Legal claims against Company
    text: You may not access or use the Service or Company Content for the primary purpose of identifying, instigating, or facilitating legal claims against Company
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
name: BigID
provenance_date: '2026-11-09'
provider_name: BigID
provider_slug: bigid
slug: bigid-eligibility
source_date: '2026-11-09'
source_filename: bigid-eligibility.yml
source_heading: Eligibility
source_page: https://bigid.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BigID\naid: bigid\nurl: https://bigid.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Legal claims against Company\n  text: You may not access or use the Service or Company Content for the primary purpose of identifying, instigating,\n    or facilitating legal claims against Company\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bigid/eligibility/bigid-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from BigID's own page on 2026-11-09.
synthetic: false
tags:
- Data Security
- DSPM
- DLP
- Privacy
- AI Security
- Data Catalog
- DSAR
- Data Discovery
- Compliance
---
