---
api_specs:
- filename: confident-cannabis-client-info-api-openapi.yml
  format: yaml
  label: Confident Cannabis Client Info API
  slug: confident-cannabis-client-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-client-info-api-openapi.yml
- filename: confident-cannabis-clients-api-openapi.yml
  format: yaml
  label: Confident Cannabis Clients API
  slug: confident-cannabis-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-clients-api-openapi.yml
- filename: confident-cannabis-lab-info-api-openapi.yml
  format: yaml
  label: Confident Cannabis Lab Info API
  slug: confident-cannabis-lab-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-lab-info-api-openapi.yml
- filename: confident-cannabis-labs-api-openapi.yml
  format: yaml
  label: Confident Cannabis Labs API
  slug: confident-cannabis-labs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-labs-api-openapi.yml
- filename: confident-cannabis-order-status-api-openapi.yml
  format: yaml
  label: Confident Cannabis Order Status API
  slug: confident-cannabis-order-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-order-status-api-openapi.yml
- filename: confident-cannabis-orders-api-openapi.yml
  format: yaml
  label: Confident Cannabis Orders API
  slug: confident-cannabis-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-orders-api-openapi.yml
- filename: confident-cannabis-reference-data-api-openapi.yml
  format: yaml
  label: Confident Cannabis Reference Data API
  slug: confident-cannabis-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-reference-data-api-openapi.yml
- filename: confident-cannabis-sample-files-api-openapi.yml
  format: yaml
  label: Confident Cannabis Sample Files API
  slug: confident-cannabis-sample-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-sample-files-api-openapi.yml
- filename: confident-cannabis-samples-api-openapi.yml
  format: yaml
  label: Confident Cannabis Samples API
  slug: confident-cannabis-samples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-samples-api-openapi.yml
- filename: confident-cannabis-test-results-api-openapi.yml
  format: yaml
  label: Confident Cannabis Test Results API
  slug: confident-cannabis-test-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/confident-cannabis/openapi/confident-cannabis-test-results-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and offered by CL from its facilities in the United States of America. CL makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: The platform is not for use by retail customers or individuals not acting on behalf of Clients or Labs.
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH CL
    value: legal age
  restricted_uses:
  - summary: No cannabis or alcohol content aimed at under-21s
    text: is intended to encourage the use of illegal substances or the use of alcohol or cannabis by individuals under the age of 21
  - summary: No use to violate laws
    text: you shall not use the Services, directly or indirectly, to enter into any transaction or other activity that violates any applicable laws, rules or regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we cannot confirm that each Registered User is who they claim to be.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Confident Cannabis
provenance_date: '2026-11-09'
provider_name: Confident Cannabis
provider_slug: confident-cannabis
slug: confident-cannabis-eligibility
source_date: '2026-11-09'
source_filename: confident-cannabis-eligibility.yml
source_heading: Eligibility
source_page: https://www.confidentlims.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Confident Cannabis\naid: confident-cannabis\nurl: https://www.confidentlims.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and offered by CL from its facilities in the United States of America. CL makes\n    no representations that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: The platform is not for use by retail customers or individuals not acting on behalf of Clients or Labs.\nrestricted_uses:\n- summary: No cannabis or alcohol content aimed at under-21s\n\
  \  text: is intended to encourage the use of illegal substances or the use of alcohol or cannabis by individuals\n    under the age of 21\n- summary: No use to violate laws\n  text: you shall not use the Services, directly or indirectly, to enter into any transaction or other activity\n    that violates any applicable laws, rules or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we cannot confirm that each Registered User is who they claim to be.\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH CL\n"
source_yaml_url: https://artifacts.apis.io/confident-cannabis/eligibility/confident-cannabis-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Confident Cannabis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cannabis
- Laboratory
- LIMS
- Testing
- Compliance
- Certificate of Analysis
- Life Sciences
---
