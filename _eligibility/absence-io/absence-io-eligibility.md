---
api_specs:
- filename: absence-io-absences-api-openapi.yml
  format: yaml
  label: Absence.io Absences API
  slug: absence-io-absences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absence-io/openapi/absence-io-absences-api-openapi.yml
- filename: absence-io-allowances-api-openapi.yml
  format: yaml
  label: Absence.io Allowances API
  slug: absence-io-allowances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absence-io/openapi/absence-io-allowances-api-openapi.yml
- filename: absence-io-departments-api-openapi.yml
  format: yaml
  label: Absence.io Departments API
  slug: absence-io-departments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absence-io/openapi/absence-io-departments-api-openapi.yml
- filename: absence-io-locations-api-openapi.yml
  format: yaml
  label: Absence.io Locations API
  slug: absence-io-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absence-io/openapi/absence-io-locations-api-openapi.yml
- filename: absence-io-reason-types-api-openapi.yml
  format: yaml
  label: Absence.io Reason Types API
  slug: absence-io-reason-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absence-io/openapi/absence-io-reason-types-api-openapi.yml
- filename: absence-io-timespans-api-openapi.yml
  format: yaml
  label: Absence.io Timespans API
  slug: absence-io-timespans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absence-io/openapi/absence-io-timespans-api-openapi.yml
- filename: absence-io-users-api-openapi.yml
  format: yaml
  label: Absence.io Users API
  slug: absence-io-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/absence-io/openapi/absence-io-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: absence.io does not provide its services to consumers but instead expressly for the commercial or independent professional activities of the Customer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misuse of the service
    text: The Customer may not misuse absence.io, in particular by publishing or disseminating illegal, defamatory or clearly pornographic or otherwise offensive content, or by using technical tools or methods which adversely affect or could adversely affect the operability of absence.io.
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
name: Absence.io
provenance_date: '2026-11-09'
provider_name: Absence.io
provider_slug: absence-io
slug: absence-io-eligibility
source_date: '2026-11-09'
source_filename: absence-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.absence.io/en/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Absence.io\naid: absence-io\nurl: https://www.absence.io/en/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: absence.io does not provide its services to consumers but instead expressly for the commercial or independent\n    professional activities of the Customer.\nrestricted_uses:\n- summary: Misuse of the service\n  text: The Customer may not misuse absence.io, in particular by publishing or disseminating illegal, defamatory\n    or clearly pornographic or otherwise offensive content, or by using technical tools\
  \ or methods which adversely\n    affect or could adversely affect the operability of absence.io.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/absence-io/eligibility/absence-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Absence.io's own page on 2026-11-09.
synthetic: false
tags:
- Absences
- Employees
- Leave Management
- Human Resources
---
