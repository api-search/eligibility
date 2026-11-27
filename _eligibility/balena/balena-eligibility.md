---
api_specs:
- filename: balena-applications-api-openapi.yml
  format: yaml
  label: Balena Applications API
  slug: balena-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/balena/openapi/balena-applications-api-openapi.yml
- filename: balena-device-tags-api-openapi.yml
  format: yaml
  label: Balena Device Tags API
  slug: balena-device-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/balena/openapi/balena-device-tags-api-openapi.yml
- filename: balena-devices-api-openapi.yml
  format: yaml
  label: Balena Devices API
  slug: balena-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/balena/openapi/balena-devices-api-openapi.yml
- filename: balena-releases-api-openapi.yml
  format: yaml
  label: Balena Releases API
  slug: balena-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/balena/openapi/balena-releases-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THESE TERMS AND CONDITIONS
    type: business
  minimum_age:
    text: You must be 13 years or older to use this Service.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: You may not use the Service for any illegal or unauthorized purpose.
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
name: Balena
provenance_date: '2026-11-09'
provider_name: Balena
provider_slug: balena
slug: balena-eligibility
source_date: '2026-11-09'
source_filename: balena-eligibility.yml
source_heading: Eligibility
source_page: https://www.balena.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Balena\naid: balena\nurl: https://www.balena.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT\n    THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THESE TERMS AND CONDITIONS\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: You may not use the Service for any illegal or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: You must be 13 years or older to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/balena/eligibility/balena-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Balena's own page on 2026-11-09.
synthetic: false
tags:
- Containers
- Device Management
- Edge
- Embedded Linux
- Fleet Management
- IoT
- OTA
- Provisioning
- Releases
---
