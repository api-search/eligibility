---
api_specs:
- filename: atlassian-compass-events-api-openapi.yml
  format: yaml
  label: Atlassian Compass Events API
  slug: atlassian-compass-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-events-api-openapi.yml
- filename: atlassian-compass-metrics-api-openapi.yml
  format: yaml
  label: Atlassian Compass Metrics API
  slug: atlassian-compass-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-metrics-api-openapi.yml
- filename: atlassian-compass-attachment-rest-controller-api-openapi.yml
  format: yaml
  label: Atlassian Compass Attachment Rest Controller API
  slug: atlassian-compass-attachment-rest-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-attachment-rest-controller-api-openapi.yml
- filename: atlassian-compass-entitlement-rest-controller-api-openapi.yml
  format: yaml
  label: Atlassian Compass Entitlement Rest Controller API
  slug: atlassian-compass-entitlement-rest-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-entitlement-rest-controller-api-openapi.yml
- filename: atlassian-compass-incoming-webhooks-rest-controller-api-openapi.yml
  format: yaml
  label: Atlassian Compass Incoming Webhooks Rest Controller API
  slug: atlassian-compass-incoming-webhooks-rest-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-incoming-webhooks-rest-controller-api-openapi.yml
- filename: atlassian-compass-package-dependencies-api-openapi.yml
  format: yaml
  label: Atlassian Compass Package Dependencies API
  slug: atlassian-compass-package-dependencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlassian-compass/openapi/atlassian-compass-package-dependencies-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “ Customer ” means the entity on behalf of which this Agreement is accepted
    type: business
  - text: or, if that does not apply, the individual accepting this Agreement.
    type: individual
  minimum_age:
    text: The Products are not intended for use by anyone under the age of 16.
    value: '16'
  restricted_uses:
  - summary: Export restrictions
    text: 'Customer must not (and must not allow anyone else to) export, re-export, transfer or disclose the Products or any direct product of the Products: (a) to (or to a national or resident of) any U.S. embargoed jurisdiction'
  - summary: Protected health information
    text: Customer must not (and must not permit anyone else to) upload to the Cloud Products (or use the Cloud Products to process) any patient, medical or other protected health information regulated by the Health Insurance Portability and Accountability Act.
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
name: Atlassian Compass
provenance_date: '2026-11-09'
provider_name: Atlassian Compass
provider_slug: atlassian-compass
slug: atlassian-compass-eligibility
source_date: '2026-11-09'
source_filename: atlassian-compass-eligibility.yml
source_heading: Eligibility
source_page: https://www.atlassian.com/legal/atlassian-customer-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlassian Compass\naid: atlassian-compass\nurl: https://www.atlassian.com/legal/atlassian-customer-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “ Customer ” means the entity on behalf of which this Agreement is accepted\n- type: individual\n  text: or, if that does not apply, the individual accepting this Agreement.\nrestricted_uses:\n- summary: Export restrictions\n  text: 'Customer must not (and must not allow anyone else to) export, re-export, transfer or disclose the Products\n    or any direct product of the Products:\
  \ (a) to (or to a national or resident of) any U.S. embargoed jurisdiction'\n- summary: Protected health information\n  text: Customer must not (and must not permit anyone else to) upload to the Cloud Products (or use the Cloud Products\n    to process) any patient, medical or other protected health information regulated by the Health Insurance Portability\n    and Accountability Act.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Products are not intended for use by anyone under the age of 16.\n"
source_yaml_url: https://artifacts.apis.io/atlassian-compass/eligibility/atlassian-compass-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Atlassian Compass's own page on 2026-11-09.
synthetic: false
tags:
- Atlassian
- Component Management
- Developer Experience
- Software Catalog
- GraphQL
---
