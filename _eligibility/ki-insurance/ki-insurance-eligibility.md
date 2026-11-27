---
api_specs:
- filename: ki-insurance-administration-api-openapi.yml
  format: yaml
  label: Ki Insurance Administration API
  slug: ki-insurance-administration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-administration-api-openapi.yml
- filename: ki-insurance-broking-houses-api-openapi.yml
  format: yaml
  label: Ki Insurance Broking Houses API
  slug: ki-insurance-broking-houses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-broking-houses-api-openapi.yml
- filename: ki-insurance-classes-of-business-api-openapi.yml
  format: yaml
  label: Ki Insurance Classes of Business API
  slug: ki-insurance-classes-of-business-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-classes-of-business-api-openapi.yml
- filename: ki-insurance-configuration-api-openapi.yml
  format: yaml
  label: Ki Insurance Configuration API
  slug: ki-insurance-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-configuration-api-openapi.yml
- filename: ki-insurance-dashboard-api-openapi.yml
  format: yaml
  label: Ki Insurance Dashboard API
  slug: ki-insurance-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-dashboard-api-openapi.yml
- filename: ki-insurance-facilities-api-openapi.yml
  format: yaml
  label: Ki Insurance Facilities API
  slug: ki-insurance-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-facilities-api-openapi.yml
- filename: ki-insurance-indications-api-openapi.yml
  format: yaml
  label: Ki Insurance Indications API
  slug: ki-insurance-indications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-indications-api-openapi.yml
- filename: ki-insurance-leads-api-openapi.yml
  format: yaml
  label: Ki Insurance Leads API
  slug: ki-insurance-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-leads-api-openapi.yml
- filename: ki-insurance-market-leaders-api-openapi.yml
  format: yaml
  label: Ki Insurance Market Leaders API
  slug: ki-insurance-market-leaders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-market-leaders-api-openapi.yml
- filename: ki-insurance-master-data-api-openapi.yml
  format: yaml
  label: Ki Insurance Master Data API
  slug: ki-insurance-master-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-master-data-api-openapi.yml
- filename: ki-insurance-pipeline-api-openapi.yml
  format: yaml
  label: Ki Insurance Pipeline API
  slug: ki-insurance-pipeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-pipeline-api-openapi.yml
- filename: ki-insurance-quotes-api-openapi.yml
  format: yaml
  label: Ki Insurance Quotes API
  slug: ki-insurance-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-quotes-api-openapi.yml
- filename: ki-insurance-risk-codes-api-openapi.yml
  format: yaml
  label: Ki Insurance Risk Codes API
  slug: ki-insurance-risk-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-risk-codes-api-openapi.yml
- filename: ki-insurance-schedule-of-values-api-openapi.yml
  format: yaml
  label: Ki Insurance Schedule of Values API
  slug: ki-insurance-schedule-of-values-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-schedule-of-values-api-openapi.yml
- filename: ki-insurance-slip-extraction-api-openapi.yml
  format: yaml
  label: Ki Insurance Slip Extraction API
  slug: ki-insurance-slip-extraction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-slip-extraction-api-openapi.yml
- filename: ki-insurance-support-api-openapi.yml
  format: yaml
  label: Ki Insurance Support API
  slug: ki-insurance-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-support-api-openapi.yml
- filename: ki-insurance-telemetry-api-openapi.yml
  format: yaml
  label: Ki Insurance Telemetry API
  slug: ki-insurance-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-telemetry-api-openapi.yml
- filename: ki-insurance-users-api-openapi.yml
  format: yaml
  label: Ki Insurance Users API
  slug: ki-insurance-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ki-insurance/openapi/ki-insurance-users-api-openapi.yml
claim_count: 2
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
  - summary: Ki Platform quote use only
    text: You may only use the Ki Platform for obtaining a quote from Ki Syndicate 1618 (“Ki”).
  - summary: No unauthorised risk placement
    text: to post any particulars of risks which you are not authorised by law to place or to conclude;
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
name: Ki Insurance
provenance_date: '2026-11-09'
provider_name: Ki Insurance
provider_slug: ki-insurance
slug: ki-insurance-eligibility
source_date: '2026-11-09'
source_filename: ki-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://app.ki-insurance.com/policies/2025/11/16/Ki_Website_Terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ki Insurance\naid: ki-insurance\nurl: https://app.ki-insurance.com/policies/2025/11/16/Ki_Website_Terms.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Ki Platform quote use only\n  text: You may only use the Ki Platform for obtaining a quote from Ki Syndicate 1618 (“Ki”).\n- summary: No unauthorised risk placement\n  text: to post any particulars of risks which you are not authorised by law to place or to conclude;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/ki-insurance/eligibility/ki-insurance-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Ki Insurance's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- United Kingdom
- Lloyd's of London
- Specialty Insurance
- Property and Casualty
- Underwriting
- Insurtech
- Brokerage
- Algorithmic Underwriting
- Reinsurance
---
