---
api_specs:
- filename: atatravel-cloud-buildings-api-openapi.yml
  format: yaml
  label: ATA Travel Buildings API
  slug: atatravel-cloud-buildings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atatravel-cloud/openapi/atatravel-cloud-buildings-api-openapi.yml
- filename: atatravel-cloud-commercial-api-openapi.yml
  format: yaml
  label: ATA Travel Commercial API
  slug: atatravel-cloud-commercial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atatravel-cloud/openapi/atatravel-cloud-commercial-api-openapi.yml
- filename: atatravel-cloud-discovery-api-openapi.yml
  format: yaml
  label: ATA Travel Discovery API
  slug: atatravel-cloud-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atatravel-cloud/openapi/atatravel-cloud-discovery-api-openapi.yml
- filename: atatravel-cloud-properties-api-openapi.yml
  format: yaml
  label: ATA Travel Properties API
  slug: atatravel-cloud-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atatravel-cloud/openapi/atatravel-cloud-properties-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Booking holds, reservation requests, and payment steps require traveler verification or an approved traveler handoff.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ATA Travel
provenance_date: '2026-11-09'
provider_name: ATA Travel
provider_slug: atatravel-cloud
slug: atatravel-cloud-eligibility
source_date: '2026-11-09'
source_filename: atatravel-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://atatravel.cloud/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ATA Travel\naid: atatravel-cloud\nurl: https://atatravel.cloud/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Booking holds, reservation requests, and payment steps require traveler verification or an approved traveler\n    handoff.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/atatravel-cloud/eligibility/atatravel-cloud-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from ATA Travel's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Artificial Intelligence
- Booking
- Accommodation
- Software-as-a-Service
- NoCommission
---
