---
api_specs:
- filename: bioflyte-alert-api-openapi.yml
  format: yaml
  label: BioFlyte Alert API
  slug: bioflyte-alert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bioflyte/openapi/bioflyte-alert-api-openapi.yml
- filename: bioflyte-client-api-openapi.yml
  format: yaml
  label: BioFlyte Client API
  slug: bioflyte-client-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bioflyte/openapi/bioflyte-client-api-openapi.yml
- filename: bioflyte-files-api-openapi.yml
  format: yaml
  label: BioFlyte Files API
  slug: bioflyte-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bioflyte/openapi/bioflyte-files-api-openapi.yml
- filename: bioflyte-filters-api-openapi.yml
  format: yaml
  label: BioFlyte Filters API
  slug: bioflyte-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bioflyte/openapi/bioflyte-filters-api-openapi.yml
- filename: bioflyte-locations-api-openapi.yml
  format: yaml
  label: BioFlyte Locations API
  slug: bioflyte-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bioflyte/openapi/bioflyte-locations-api-openapi.yml
- filename: bioflyte-organization-api-openapi.yml
  format: yaml
  label: BioFlyte Organization API
  slug: bioflyte-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bioflyte/openapi/bioflyte-organization-api-openapi.yml
- filename: bioflyte-permissions-api-openapi.yml
  format: yaml
  label: BioFlyte Permissions API
  slug: bioflyte-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bioflyte/openapi/bioflyte-permissions-api-openapi.yml
- filename: bioflyte-requesthelp-api-openapi.yml
  format: yaml
  label: BioFlyte Request Help API
  slug: bioflyte-requesthelp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bioflyte/openapi/bioflyte-requesthelp-api-openapi.yml
- filename: bioflyte-test-api-openapi.yml
  format: yaml
  label: BioFlyte Test API
  slug: bioflyte-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bioflyte/openapi/bioflyte-test-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims that our Site or any of its Content ... is accessible, available or appropriate outside of the United States.
  minimum_age:
    text: BioFlyte does not intend that any portion of the Website will be accessed or used by children under the age of 13, and such use is prohibited.
    value: '13'
  restricted_uses:
  - summary: Export and illegal use
    text: You may not use or export or re-export the materials or services at this Site or any copy or adaptation in violation of any applicable laws or regulations including without limitation U.S. export laws and regulations.
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
name: BioFlyte
provenance_date: '2026-11-09'
provider_name: BioFlyte
provider_slug: bioflyte
slug: bioflyte-eligibility
source_date: '2026-11-09'
source_filename: bioflyte-eligibility.yml
source_heading: Eligibility
source_page: https://www.bioflyte.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BioFlyte\naid: bioflyte\nurl: https://www.bioflyte.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims that our Site or any of its Content ... is accessible, available or appropriate outside\n    of the United States.\nentity_types: []\nrestricted_uses:\n- summary: Export and illegal use\n  text: You may not use or export or re-export the materials or services at this Site or any copy or adaptation\n    in violation of any applicable laws or regulations including without limitation U.S. export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: BioFlyte does not intend that any portion of the Website will be accessed or used by children under the\n    age of 13, and such use is prohibited.\n"
source_yaml_url: https://artifacts.apis.io/bioflyte/eligibility/bioflyte-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BioFlyte's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biodefense
- Biothreat Detection
- Mass Spectrometry
- Aerosol Monitoring
- Homeland Security
- Critical Infrastructure
- Public Safety
- Sensors
- Hardware
- Artificial Intelligence
- Content
---
