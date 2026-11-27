---
api_specs:
- filename: cloudkit-assets-api-openapi.yml
  format: yaml
  label: Apple CloudKit Assets API
  slug: cloudkit-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudkit/openapi/cloudkit-assets-api-openapi.yml
- filename: cloudkit-changes-api-openapi.yml
  format: yaml
  label: Apple CloudKit Changes API
  slug: cloudkit-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudkit/openapi/cloudkit-changes-api-openapi.yml
- filename: cloudkit-records-api-openapi.yml
  format: yaml
  label: Apple CloudKit Records API
  slug: cloudkit-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudkit/openapi/cloudkit-records-api-openapi.yml
- filename: cloudkit-subscriptions-api-openapi.yml
  format: yaml
  label: Apple CloudKit Subscriptions API
  slug: cloudkit-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudkit/openapi/cloudkit-subscriptions-api-openapi.yml
- filename: cloudkit-tokens-api-openapi.yml
  format: yaml
  label: Apple CloudKit Tokens API
  slug: cloudkit-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudkit/openapi/cloudkit-tokens-api-openapi.yml
- filename: cloudkit-users-api-openapi.yml
  format: yaml
  label: Apple CloudKit Users API
  slug: cloudkit-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudkit/openapi/cloudkit-users-api-openapi.yml
- filename: cloudkit-zones-api-openapi.yml
  format: yaml
  label: Apple CloudKit Zones API
  slug: cloudkit-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloudkit/openapi/cloudkit-zones-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service, or any feature or part thereof, may not be available in all languages or in all countries
  entity_types:
  - text: The Service is only available to individuals aged 13 years or older
    type: individual
  minimum_age:
    text: The Service is only available to individuals aged 13 years or older (or equivalent minimum age in the relevant jurisdiction)
    value: '13'
  restricted_uses:
  - summary: No protected health information
    text: you will not use any component, function or other facility of the Service to create, receive, maintain or transmit any “protected health information”
  - summary: No export to embargoed countries or listed parties
    text: the Software may not be exported or re-exported (a) into any U.S. embargoed countries or (b) to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals
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
name: Apple CloudKit
provenance_date: '2026-11-09'
provider_name: Apple CloudKit
provider_slug: cloudkit
slug: cloudkit-eligibility
source_date: '2026-11-09'
source_filename: cloudkit-eligibility.yml
source_heading: Eligibility
source_page: https://www.apple.com/legal/internet-services/icloud/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apple CloudKit\naid: cloudkit\nurl: https://www.apple.com/legal/internet-services/icloud/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service, or any feature or part thereof, may not be available in all languages or in all countries\nentity_types:\n- type: individual\n  text: The Service is only available to individuals aged 13 years or older\nrestricted_uses:\n- summary: No protected health information\n  text: you will not use any component, function or other facility of the Service to create, receive, maintain or\n    transmit any “protected health information”\n\
  - summary: No export to embargoed countries or listed parties\n  text: the Software may not be exported or re-exported (a) into any U.S. embargoed countries or (b) to anyone on\n    the U.S. Treasury Department’s list of Specially Designated Nationals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is only available to individuals aged 13 years or older (or equivalent minimum age in the relevant\n    jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/cloudkit/eligibility/cloudkit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Apple CloudKit's own page on 2026-11-09.
synthetic: false
tags:
- Apple
- Cloud Storage
- CloudKit
- Database
- iCloud
- Mobile
- Sync
- Web Services
---
