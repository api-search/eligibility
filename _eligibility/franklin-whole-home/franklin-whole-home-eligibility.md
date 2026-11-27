---
api_specs:
- filename: franklin-whole-home-authentication-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Authentication API
  slug: franklin-whole-home-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-authentication-api-openapi.yml
- filename: franklin-whole-home-device-data-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Device Data API
  slug: franklin-whole-home-device-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-device-data-api-openapi.yml
- filename: franklin-whole-home-devices-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Devices API
  slug: franklin-whole-home-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-devices-api-openapi.yml
- filename: franklin-whole-home-grid-events-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Grid Events API
  slug: franklin-whole-home-grid-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-grid-events-api-openapi.yml
- filename: franklin-whole-home-groups-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Groups API
  slug: franklin-whole-home-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-groups-api-openapi.yml
- filename: franklin-whole-home-modification-records-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Modification Records API
  slug: franklin-whole-home-modification-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-modification-records-api-openapi.yml
- filename: franklin-whole-home-sites-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Sites API
  slug: franklin-whole-home-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-sites-api-openapi.yml
- filename: franklin-whole-home-sunrun-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Sunrun API
  slug: franklin-whole-home-sunrun-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-sunrun-api-openapi.yml
- filename: franklin-whole-home-sunrun-sites-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Sunrun Sites API
  slug: franklin-whole-home-sunrun-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-sunrun-sites-api-openapi.yml
- filename: franklin-whole-home-sunrun-system-setup-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Sunrun System Setup API
  slug: franklin-whole-home-sunrun-system-setup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-sunrun-system-setup-api-openapi.yml
- filename: franklin-whole-home-system-settings-api-openapi.yml
  format: yaml
  label: Franklin Whole Home System Settings API
  slug: franklin-whole-home-system-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-system-settings-api-openapi.yml
- filename: franklin-whole-home-warnings-and-events-api-openapi.yml
  format: yaml
  label: Franklin Whole Home Warnings and Events API
  slug: franklin-whole-home-warnings-and-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/franklin-whole-home/openapi/franklin-whole-home-warnings-and-events-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction, if higher) to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction, if higher) to use the Service.
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: You must not use the Service for High-Risk Activities, and FranklinWH will not be liable for use of the Service for High-Risk Activities.
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
name: Franklin Whole Home
provenance_date: '2026-11-09'
provider_name: Franklin Whole Home
provider_slug: franklin-whole-home
slug: franklin-whole-home-eligibility
source_date: '2026-11-09'
source_filename: franklin-whole-home-eligibility.yml
source_heading: Eligibility
source_page: https://www.franklinwh.com/cybersecurity/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Franklin Whole Home\naid: franklin-whole-home\nurl: https://www.franklinwh.com/cybersecurity/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction, if higher) to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: High-risk activities\n  text:\
  \ You must not use the Service for High-Risk Activities, and FranklinWH will not be liable for use of the\n    Service for High-Risk Activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction, if higher) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/franklin-whole-home/eligibility/franklin-whole-home-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Franklin Whole Home's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Energy Storage
- Home Energy Management
- Solar
- Batteries
- IoT
- Smart Home
- Electric Vehicles
- Cleantech
- Device Telemetry
---
