---
api_specs:
- filename: greynoise-callback-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence Callback API
  slug: greynoise-callback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-callback-api-openapi.yml
- filename: greynoise-community-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence Community API
  slug: greynoise-community-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-community-api-openapi.yml
- filename: greynoise-cve-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence CVE API
  slug: greynoise-cve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-cve-api-openapi.yml
- filename: greynoise-gnql-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence GNQL API
  slug: greynoise-gnql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-gnql-api-openapi.yml
- filename: greynoise-ip-lookup-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence IP Lookup API
  slug: greynoise-ip-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-ip-lookup-api-openapi.yml
- filename: greynoise-ip-timeline-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence IP Timeline API
  slug: greynoise-ip-timeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-ip-timeline-api-openapi.yml
- filename: greynoise-recall-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence Recall API
  slug: greynoise-recall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-recall-api-openapi.yml
- filename: greynoise-sessions-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence Sessions API
  slug: greynoise-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-sessions-api-openapi.yml
- filename: greynoise-tags-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence Tags API
  slug: greynoise-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-tags-api-openapi.yml
- filename: greynoise-utility-api-openapi.yml
  format: yaml
  label: GreyNoise Intelligence Utility API
  slug: greynoise-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greynoise/openapi/greynoise-utility-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you use GreyNoise Products on behalf of an entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: you are of legal age to enter into a binding agreement
    value: null
  restricted_uses:
  - summary: No AI model training with GreyNoise Data
    text: use GreyNoise Data, in whole or in part, to (A) train, develop, fine-tune, validate, modify, update, or otherwise improve any machine learning model, artificial intelligence system, or similar technology
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
name: GreyNoise Intelligence
provenance_date: '2026-11-09'
provider_name: GreyNoise Intelligence
provider_slug: greynoise
slug: greynoise-eligibility
source_date: '2026-11-09'
source_filename: greynoise-eligibility.yml
source_heading: Eligibility
source_page: https://www.greynoise.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GreyNoise Intelligence\naid: greynoise\nurl: https://www.greynoise.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you use GreyNoise Products on behalf of an entity, you represent and warrant that you have the authority\n    to bind that entity\nrestricted_uses:\n- summary: No AI model training with GreyNoise Data\n  text: use GreyNoise Data, in whole or in part, to (A) train, develop, fine-tune, validate, modify, update, or\n    otherwise improve any machine learning model, artificial intelligence system, or similar technology\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to enter into a binding agreement\n"
source_yaml_url: https://artifacts.apis.io/greynoise/eligibility/greynoise-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from GreyNoise Intelligence's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Threat Intelligence
- Cybersecurity
- IP Reputation
- Vulnerability Management
- Network Telemetry
- SOC Automation
- Public APIs
---
