---
api_specs:
- filename: findadoctor-si-about-api-openapi.yml
  format: yaml
  label: findadoctor-si About API
  slug: findadoctor-si-about-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-about-api-openapi.yml
- filename: findadoctor-si-doctors-api-openapi.yml
  format: yaml
  label: findadoctor-si Doctors API
  slug: findadoctor-si-doctors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-doctors-api-openapi.yml
- filename: findadoctor-si-gp-practices-api-openapi.yml
  format: yaml
  label: findadoctor-si Gp Practices API
  slug: findadoctor-si-gp-practices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-gp-practices-api-openapi.yml
- filename: findadoctor-si-procedure-volumes-api-openapi.yml
  format: yaml
  label: findadoctor-si Procedure Volumes API
  slug: findadoctor-si-procedure-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-procedure-volumes-api-openapi.yml
- filename: findadoctor-si-procedures-api-openapi.yml
  format: yaml
  label: findadoctor-si Procedures API
  slug: findadoctor-si-procedures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-procedures-api-openapi.yml
- filename: findadoctor-si-search-api-openapi.yml
  format: yaml
  label: findadoctor-si Search API
  slug: findadoctor-si-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-search-api-openapi.yml
- filename: findadoctor-si-specialties-api-openapi.yml
  format: yaml
  label: findadoctor-si Specialties API
  slug: findadoctor-si-specialties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-specialties-api-openapi.yml
- filename: findadoctor-si-terms-api-openapi.yml
  format: yaml
  label: findadoctor-si Terms API
  slug: findadoctor-si-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-terms-api-openapi.yml
- filename: findadoctor-si-waitlist-api-openapi.yml
  format: yaml
  label: findadoctor-si Waitlist API
  slug: findadoctor-si-waitlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findadoctor-si/openapi/findadoctor-si-waitlist-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - NZ
    - FR
    text: Read-only directories of doctors in the United States, New Zealand and France
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No bulk copying, marketing contact, or harmful use
    text: Do not use the service to copy a directory in bulk, to contact doctors for marketing, or in a way that harms the service or other users.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: No sign-up.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: findadoctor-si
provenance_date: '2026-11-09'
provider_name: findadoctor-si
provider_slug: findadoctor-si
slug: findadoctor-si-eligibility
source_date: '2026-11-09'
source_filename: findadoctor-si-eligibility.yml
source_heading: Eligibility
source_page: https://findadoctor.si/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: findadoctor-si\naid: findadoctor-si\nurl: https://findadoctor.si/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - NZ\n  - FR\n  excluded: []\n  text: Read-only directories of doctors in the United States, New Zealand and France\nentity_types: []\nrestricted_uses:\n- summary: No bulk copying, marketing contact, or harmful use\n  text: Do not use the service to copy a directory in bulk, to contact doctors for marketing, or in a way that harms\n    the service or other users.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: No sign-up.\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/findadoctor-si/eligibility/findadoctor-si-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from findadoctor-si's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Data
- Artificial Intelligence
- Doctor
- International
---
