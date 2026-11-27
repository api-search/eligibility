---
api_specs:
- filename: spektr-action-api-api-openapi.yml
  format: yaml
  label: Spektr Action API
  slug: spektr-action-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spektr/openapi/spektr-action-api-api-openapi.yml
- filename: spektr-events-api-api-openapi.yml
  format: yaml
  label: Spektr Events API
  slug: spektr-events-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spektr/openapi/spektr-events-api-api-openapi.yml
- filename: spektr-execution-api-api-openapi.yml
  format: yaml
  label: Spektr Execution API
  slug: spektr-execution-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spektr/openapi/spektr-execution-api-api-openapi.yml
- filename: spektr-import-api-api-openapi.yml
  format: yaml
  label: Spektr Import API
  slug: spektr-import-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spektr/openapi/spektr-import-api-api-openapi.yml
- filename: spektr-orchestration-api-api-openapi.yml
  format: yaml
  label: Spektr Orchestration API
  slug: spektr-orchestration-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spektr/openapi/spektr-orchestration-api-api-openapi.yml
- filename: spektr-records-api-api-openapi.yml
  format: yaml
  label: Spektr Records API
  slug: spektr-records-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spektr/openapi/spektr-records-api-api-openapi.yml
- filename: spektr-transaction-definitions-api-openapi.yml
  format: yaml
  label: Spektr Transaction Definitions API
  slug: spektr-transaction-definitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spektr/openapi/spektr-transaction-definitions-api-openapi.yml
- filename: spektr-transactions-api-openapi.yml
  format: yaml
  label: Spektr Transactions API
  slug: spektr-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spektr/openapi/spektr-transactions-api-openapi.yml
- filename: spektr-workspace-fields-api-api-openapi.yml
  format: yaml
  label: Spektr Workspace Fields API
  slug: spektr-workspace-fields-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spektr/openapi/spektr-workspace-fields-api-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to any law or regulation
  entity_types:
  - text: If you are accepting the Terms on behalf of a company, organization, or other legal entity, you represent and warrant that you have the authority to bind such entity to the Terms.
    type: business
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: No uploading own data to Demo
    text: Users are, therefore, not permitted to upload, input, or ingest their own data into the Demo.
  - summary: Demo limited to mock data
    text: The Demo is designed to operate solely with the provided mock or synthetic data.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we retain the right to review the information through third-party service providers before granting access to the Demo
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Spektr
provenance_date: '2026-11-10'
provider_name: Spektr
provider_slug: spektr
slug: spektr-eligibility
source_date: '2026-11-10'
source_filename: spektr-eligibility.yml
source_heading: Eligibility
source_page: https://www.spektr.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spektr\naid: spektr\nurl: https://www.spektr.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to any law or regulation\nentity_types:\n- type: business\n  text: If you are accepting the Terms on behalf of a company, organization, or other legal entity, you represent\n    and warrant that you have the authority to bind such entity to the Terms.\nrestricted_uses:\n\
  - summary: No uploading own data to Demo\n  text: Users are, therefore, not permitted to upload, input, or ingest their own data into the Demo.\n- summary: Demo limited to mock data\n  text: The Demo is designed to operate solely with the provided mock or synthetic data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we retain the right to review the information through third-party service providers before granting access\n    to the Demo\nminimum_age:\n  value: null\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/spektr/eligibility/spektr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Spektr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compliance
- RegTech
- KYB
- KYC
- Onboarding
- Transaction Monitoring
- Financial Services
- Artificial Intelligence
- Enterprise
---
