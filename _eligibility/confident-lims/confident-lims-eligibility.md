---
api_specs:
- filename: confident-lims-client-info-api-openapi.yml
  format: yaml
  label: Confident LIMS Client Info API
  slug: confident-lims-client-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-client-info-api-openapi.yml
- filename: confident-lims-clients-api-openapi.yml
  format: yaml
  label: Confident LIMS Clients API
  slug: confident-lims-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-clients-api-openapi.yml
- filename: confident-lims-lab-info-api-openapi.yml
  format: yaml
  label: Confident LIMS Lab Info API
  slug: confident-lims-lab-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-lab-info-api-openapi.yml
- filename: confident-lims-labs-api-openapi.yml
  format: yaml
  label: Confident LIMS Labs API
  slug: confident-lims-labs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-labs-api-openapi.yml
- filename: confident-lims-order-status-api-openapi.yml
  format: yaml
  label: Confident LIMS Order Status API
  slug: confident-lims-order-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-order-status-api-openapi.yml
- filename: confident-lims-orders-api-openapi.yml
  format: yaml
  label: Confident LIMS Orders API
  slug: confident-lims-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-orders-api-openapi.yml
- filename: confident-lims-reference-data-api-openapi.yml
  format: yaml
  label: Confident LIMS Reference Data API
  slug: confident-lims-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-reference-data-api-openapi.yml
- filename: confident-lims-sample-files-api-openapi.yml
  format: yaml
  label: Confident LIMS Sample Files API
  slug: confident-lims-sample-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-sample-files-api-openapi.yml
- filename: confident-lims-samples-api-openapi.yml
  format: yaml
  label: Confident LIMS Samples API
  slug: confident-lims-samples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-samples-api-openapi.yml
- filename: confident-lims-test-results-api-openapi.yml
  format: yaml
  label: Confident LIMS Test Results API
  slug: confident-lims-test-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-lims/openapi/confident-lims-test-results-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and offered by CL from its facilities in the United States of America.
  entity_types:
  - text: The platform is not for use by retail customers or individuals not acting on behalf of Clients or Labs.
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH CL
    value: legal age
  restricted_uses:
  - summary: No content encouraging underage alcohol or cannabis use
    text: is intended to encourage the use of illegal substances or the use of alcohol or cannabis by individuals under the age of 21
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
name: Confident LIMS
provenance_date: '2026-11-09'
provider_name: Confident LIMS
provider_slug: confident-lims
slug: confident-lims-eligibility
source_date: '2026-11-09'
source_filename: confident-lims-eligibility.yml
source_heading: Eligibility
source_page: https://www.confidentlims.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Confident LIMS\naid: confident-lims\nurl: https://www.confidentlims.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and offered by CL from its facilities in the United States of America.\nentity_types:\n- type: business\n  text: The platform is not for use by retail customers or individuals not acting on behalf of Clients or Labs.\nrestricted_uses:\n- summary: No content encouraging underage alcohol or cannabis use\n  text: is intended to encourage the use of illegal substances or the use of alcohol or cannabis by individuals\n\
  \    under the age of 21\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH CL\n"
source_yaml_url: https://artifacts.apis.io/confident-lims/eligibility/confident-lims-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Confident LIMS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- LIMS
- Laboratory Information Management
- Analytical Testing
- Cannabis Testing
- Compliance
- Sample Management
- Lab Software
---
