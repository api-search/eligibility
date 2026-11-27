---
api_specs:
- filename: foundriesio-openapi-generated.yml
  format: yaml
  label: Foundries.io API
  slug: foundriesio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foundriesio/openapi/_ae-authored/foundriesio-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: The FoundriesFactory Service may not be available or for use in all countries. The US government currently maintains comprehensive economic sanctions or an embargo against Cuba, Iran, North Korea, Syria, and the Crimea and so-called Donetsk People's Republic and Luhansk People's Republic regions of Ukraine
  entity_types:
  - text: the person or legal entity (“ Customer ”) that has executed an Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competitive product builds
    text: Customer shall not access the FoundriesFactory Service in order to (a) build a competitive product or service
  - summary: Export and sanctions restrictions
    text: Customer warrants that neither it, nor its subsidiaries, affiliates, or agents, will directly or indirectly export, re-export, transfer or release (collectively, “ Export ”) any Foundries.io Technology
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Foundries.io
provenance_date: '2026-11-09'
provider_name: Foundries.io
provider_slug: foundriesio
slug: foundriesio-eligibility
source_date: '2026-11-09'
source_filename: foundriesio-eligibility.yml
source_heading: Eligibility
source_page: https://www.foundries.io/company/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Foundries.io\naid: foundriesio\nurl: https://www.foundries.io/company/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: The FoundriesFactory Service may not be available or for use in all countries. The US government currently\n    maintains comprehensive economic sanctions or an embargo against Cuba, Iran, North Korea, Syria, and the Crimea\n    and so-called Donetsk People's Republic and Luhansk People's Republic regions of Ukraine\nentity_types:\n- type: business\n  text: the person or legal entity (“ Customer ”) that has executed\
  \ an Order Form\nrestricted_uses:\n- summary: No competitive product builds\n  text: Customer shall not access the FoundriesFactory Service in order to (a) build a competitive product or service\n- summary: Export and sanctions restrictions\n  text: Customer warrants that neither it, nor its subsidiaries, affiliates, or agents, will directly or indirectly\n    export, re-export, transfer or release (collectively, “ Export ”) any Foundries.io Technology\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/foundriesio/eligibility/foundriesio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Foundries.io's own page on 2026-11-09.
synthetic: false
tags:
- IoT
- Embedded Linux
- Edge Computing
- Device Management
- Secure-Updates
---
