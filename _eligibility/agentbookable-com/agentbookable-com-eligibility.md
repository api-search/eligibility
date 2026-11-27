---
api_specs:
- filename: agentbookable-com-availability-api-openapi.yml
  format: yaml
  label: Agentbookable Availability API
  slug: agentbookable-com-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-availability-api-openapi.yml
- filename: agentbookable-com-bookings-api-openapi.yml
  format: yaml
  label: Agentbookable Bookings API
  slug: agentbookable-com-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-bookings-api-openapi.yml
- filename: agentbookable-com-discovery-api-openapi.yml
  format: yaml
  label: Agentbookable Discovery API
  slug: agentbookable-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-discovery-api-openapi.yml
- filename: agentbookable-com-mandates-api-openapi.yml
  format: yaml
  label: Agentbookable Mandates API
  slug: agentbookable-com-mandates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-mandates-api-openapi.yml
- filename: agentbookable-com-services-api-openapi.yml
  format: yaml
  label: Agentbookable Services API
  slug: agentbookable-com-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentbookable-com/openapi/agentbookable-com-services-api-openapi.yml
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
  restricted_uses:
  - summary: Public demo abuse
    text: Do not abuse the public demo; use throwaway customer details there.
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
name: Agentbookable
provenance_date: '2026-11-09'
provider_name: Agentbookable
provider_slug: agentbookable-com
slug: agentbookable-com-eligibility
source_date: '2026-11-09'
source_filename: agentbookable-com-eligibility.yml
source_heading: Eligibility
source_page: https://agentbookable.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agentbookable\naid: agentbookable-com\nurl: https://agentbookable.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Public demo abuse\n  text: Do not abuse the public demo; use throwaway customer details there.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentbookable-com/eligibility/agentbookable-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Agentbookable's own page on 2026-11-09.
synthetic: false
tags:
- Booking
- Artificial Intelligence
- Scheduling
- Integration
- Automation
- Company
---
