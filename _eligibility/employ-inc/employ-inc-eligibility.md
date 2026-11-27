---
api_specs:
- filename: employ-inc-status-api-openapi.yml
  format: yaml
  label: Employ Inc Status API
  slug: employ-inc-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/employ-inc/openapi/employ-inc-status-api-openapi.yml
- filename: employ-inc-components-api-openapi.yml
  format: yaml
  label: Employ Components API
  slug: employ-inc-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/employ-inc/openapi/employ-inc-components-api-openapi.yml
- filename: employ-inc-incidents-api-openapi.yml
  format: yaml
  label: Employ Incidents API
  slug: employ-inc-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/employ-inc/openapi/employ-inc-incidents-api-openapi.yml
- filename: employ-inc-maintenance-api-openapi.yml
  format: yaml
  label: Employ Maintenance API
  slug: employ-inc-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/employ-inc/openapi/employ-inc-maintenance-api-openapi.yml
- filename: employ-inc-summary-api-openapi.yml
  format: yaml
  label: Employ Summary API
  slug: employ-inc-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/employ-inc/openapi/employ-inc-summary-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer represents that the individual executing the Order Form is entering into this Agreement on behalf of the entity identified on the Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions and embargoed countries
    text: Customer may not provide to any person or export or re-export or allow the export or re-export of the Services
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
name: Employ
provenance_date: '2026-11-09'
provider_name: Employ
provider_slug: employ-inc
slug: employ-inc-eligibility
source_date: '2026-11-09'
source_filename: employ-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.employinc.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Employ\naid: employ-inc\nurl: https://www.employinc.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer represents that the individual executing the Order Form is entering into this Agreement on behalf\n    of the entity identified on the Order Form\nrestricted_uses:\n- summary: Export restrictions and embargoed countries\n  text: Customer may not provide to any person or export or re-export or allow the export or re-export of the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/employ-inc/eligibility/employ-inc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Employ's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- Recruiting
- Talent Acquisition
- Applicant Tracking
- Hiring
- Content
- Event
- Status
---
