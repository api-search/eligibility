---
api_specs:
- filename: applytovolunteer-com-applications-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Applications API
  slug: applytovolunteer-com-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-applications-api-openapi.yml
- filename: applytovolunteer-com-auth-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Auth API
  slug: applytovolunteer-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-auth-api-openapi.yml
- filename: applytovolunteer-com-conversions-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Conversions API
  slug: applytovolunteer-com-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-conversions-api-openapi.yml
- filename: applytovolunteer-com-demos-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Demos API
  slug: applytovolunteer-com-demos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-demos-api-openapi.yml
- filename: applytovolunteer-com-forms-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Forms API
  slug: applytovolunteer-com-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-forms-api-openapi.yml
- filename: applytovolunteer-com-me-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Me API
  slug: applytovolunteer-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-me-api-openapi.yml
- filename: applytovolunteer-com-public-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Public API
  slug: applytovolunteer-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-public-api-openapi.yml
- filename: applytovolunteer-com-tools-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Tools API
  slug: applytovolunteer-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-tools-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Organizations are responsible for the forms they publish and the applications they collect.
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Legal flags are not legal advice
    text: Legal flags (for example SSN or criminal-history questions) are flags, not legal advice.
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
name: ApplyToVolunteer
provenance_date: '2026-11-09'
provider_name: ApplyToVolunteer
provider_slug: applytovolunteer-com
slug: applytovolunteer-com-eligibility
source_date: '2026-11-09'
source_filename: applytovolunteer-com-eligibility.yml
source_heading: Eligibility
source_page: https://applytovolunteer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ApplyToVolunteer\naid: applytovolunteer-com\nurl: https://applytovolunteer.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Organizations are responsible for the forms they publish and the applications they collect.\nrestricted_uses:\n- summary: Legal flags are not legal advice\n  text: Legal flags (for example SSN or criminal-history questions) are flags, not legal advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/applytovolunteer-com/eligibility/applytovolunteer-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ApplyToVolunteer's own page on 2026-11-09.
synthetic: false
tags:
- Volunteer
- Forms
- Software-as-a-Service
- Non-Profit
- Platform
---
