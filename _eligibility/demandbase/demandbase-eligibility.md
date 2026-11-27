---
api_specs:
- filename: demandbase-activities-management-api-openapi.yml
  format: yaml
  label: Demandbase Activities Management API
  slug: demandbase-activities-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-activities-management-api-openapi.yml
- filename: demandbase-asynchronous-batch-api-api-openapi.yml
  format: yaml
  label: Demandbase Asynchronous (Batch) API
  slug: demandbase-asynchronous-batch-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-asynchronous-batch-api-api-openapi.yml
- filename: demandbase-auth-api-openapi.yml
  format: yaml
  label: Demandbase Auth API
  slug: demandbase-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-auth-api-openapi.yml
- filename: demandbase-company-intent-api-openapi.yml
  format: yaml
  label: Demandbase Company Intent API
  slug: demandbase-company-intent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-company-intent-api-openapi.yml
- filename: demandbase-create-export-job-api-openapi.yml
  format: yaml
  label: Demandbase Create Export Job API
  slug: demandbase-create-export-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-create-export-job-api-openapi.yml
- filename: demandbase-credit-usage-api-openapi.yml
  format: yaml
  label: Demandbase Credit Usage API
  slug: demandbase-credit-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-credit-usage-api-openapi.yml
- filename: demandbase-custom-sources-api-openapi.yml
  format: yaml
  label: Demandbase Custom Sources API
  slug: demandbase-custom-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-custom-sources-api-openapi.yml
- filename: demandbase-field-mappings-api-openapi.yml
  format: yaml
  label: Demandbase Field Mappings API
  slug: demandbase-field-mappings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-field-mappings-api-openapi.yml
- filename: demandbase-get-fields-api-openapi.yml
  format: yaml
  label: Demandbase Get Fields API
  slug: demandbase-get-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-get-fields-api-openapi.yml
- filename: demandbase-get-job-details-api-openapi.yml
  format: yaml
  label: Demandbase Get Job Details API
  slug: demandbase-get-job-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-get-job-details-api-openapi.yml
- filename: demandbase-get-reference-data-api-openapi.yml
  format: yaml
  label: Demandbase Get Reference Data API
  slug: demandbase-get-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-get-reference-data-api-openapi.yml
- filename: demandbase-import-job-api-openapi.yml
  format: yaml
  label: Demandbase Import Job API
  slug: demandbase-import-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-import-job-api-openapi.yml
- filename: demandbase-reference-tables-api-openapi.yml
  format: yaml
  label: Demandbase Reference Tables API
  slug: demandbase-reference-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-reference-tables-api-openapi.yml
- filename: demandbase-subscription-api-api-openapi.yml
  format: yaml
  label: Demandbase Subscription API
  slug: demandbase-subscription-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-subscription-api-api-openapi.yml
- filename: demandbase-sync-api-api-openapi.yml
  format: yaml
  label: Demandbase Sync API
  slug: demandbase-sync-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-sync-api-api-openapi.yml
- filename: demandbase-user-management-api-openapi.yml
  format: yaml
  label: Demandbase User Management API
  slug: demandbase-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/demandbase/openapi/demandbase-user-management-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Information Demandbase publishes on the Internet may contain references to products that are not announced or available in your country.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only
    text: The use authorized under this agreement is non-commercial in nature
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
name: Demandbase
provenance_date: '2026-11-09'
provider_name: Demandbase
provider_slug: demandbase
slug: demandbase-eligibility
source_date: '2026-11-09'
source_filename: demandbase-eligibility.yml
source_heading: Eligibility
source_page: https://www.demandbase.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Demandbase\naid: demandbase\nurl: https://www.demandbase.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Information Demandbase publishes on the Internet may contain references to products that are not announced\n    or available in your country.\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: The use authorized under this agreement is non-commercial in nature\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/demandbase/eligibility/demandbase-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Demandbase's own page on 2026-11-09.
synthetic: false
tags:
- Account Based Marketing
- Advertising
- AI Agents
- B2B Marketing
- Company Data
- Contact Data
- Data Enrichment
- Intent Data
- MCP
- Personalization
- Sales Intelligence
- Technographics
---
