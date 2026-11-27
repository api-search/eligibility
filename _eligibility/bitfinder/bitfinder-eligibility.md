---
api_specs:
- filename: bitfinder-air-data-api-openapi.yml
  format: yaml
  label: Bitfinder Air Data API
  slug: bitfinder-air-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitfinder/openapi/bitfinder-air-data-api-openapi.yml
- filename: bitfinder-devices-api-openapi.yml
  format: yaml
  label: Bitfinder Devices API
  slug: bitfinder-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitfinder/openapi/bitfinder-devices-api-openapi.yml
- filename: bitfinder-user-api-openapi.yml
  format: yaml
  label: Bitfinder User API
  slug: bitfinder-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitfinder/openapi/bitfinder-user-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: the Products and Services provided or accessed through or on the Sites are not available to all persons or in all countries.
  entity_types:
  - text: you represent that you are of sufficient legal age in your jurisdiction or residence to use or access the services and enter into this agreement.
    type: individual
  - text: you represent and warrant that you have the right, authority and capacity to accept and agree to these terms on behalf of yourself or the entity you represent
    type: business
  minimum_age:
    text: Any use or access to the Services by anyone under the age of 18 is strictly prohibited and is a violation of these Terms.
    value: '18'
  restricted_uses:
  - summary: Not for life-safety or critical use
    text: YOU AGREE THAT YOU WILL NOT RELY ON THE SERVICES FOR ANY LIFE SAFETY OR CRITICAL PURPOSES.
  - summary: Not certified for emergency response
    text: the Products and Services, whether standing alone or when interfaced with third-party products or services are not certified for emergency response.
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
name: Bitfinder
provenance_date: '2026-11-09'
provider_name: Bitfinder
provider_slug: bitfinder
slug: bitfinder-eligibility
source_date: '2026-11-09'
source_filename: bitfinder-eligibility.yml
source_heading: Eligibility
source_page: https://getawair.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bitfinder\naid: bitfinder\nurl: https://getawair.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: the Products and Services provided or accessed through or on the Sites are not available to all persons\n    or in all countries.\nentity_types:\n- type: individual\n  text: you represent that you are of sufficient legal age in your jurisdiction or residence to use or access the\n    services and enter into this agreement.\n- type: business\n  text: you represent and warrant that you have the right, authority and capacity to accept and agree to these\
  \ terms\n    on behalf of yourself or the entity you represent\nrestricted_uses:\n- summary: Not for life-safety or critical use\n  text: YOU AGREE THAT YOU WILL NOT RELY ON THE SERVICES FOR ANY LIFE SAFETY OR CRITICAL PURPOSES.\n- summary: Not certified for emergency response\n  text: the Products and Services, whether standing alone or when interfaced with third-party products or services\n    are not certified for emergency response.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the Services by anyone under the age of 18 is strictly prohibited and is a violation\n    of these Terms.\n"
source_yaml_url: https://artifacts.apis.io/bitfinder/eligibility/bitfinder-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Bitfinder's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Air Quality
- IoT
- Environmental Monitoring
- Smart Home
- Sensors
- Health
- Developer API
---
