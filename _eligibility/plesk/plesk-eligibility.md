---
api_specs:
- filename: plesk-openapi-generated.yml
  format: yaml
  label: Plesk API
  slug: plesk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plesk/openapi/_ae-authored/plesk-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    - CU
    - IR
    - KP
    served: []
    text: 'you are not located, organized or ordinarily resident in, and will not use or make available the Software, including any AI Feature, in or to, the Russian Federation or Belarus. Also excluded: countries under comprehensive sanctions or embargo, including Cuba, Iran, North Korea.'
  entity_types:
  - text: a legal contract between you, as either an individual or an Entity (as defined below)
    type: individual
  - text: IF YOU ARE ACCEPTING THIS AGREEMENT ON BEHALF OF A COMPANY, ORGANIZATION, EDUCATIONAL INSTITUTION, OR AGENCY
    type: business
  - text: If the Software is acquired by or on behalf of an agency, department, or other entity of the U.S. Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned jurisdictions and persons
    text: neither you nor any End User to whom you make the Software available is listed on, or owned 50 percent or more or controlled by one or more persons listed on, any sanctions list
  - summary: Weapons and prohibited end uses
    text: You also agree that you will not use the Software for any purposes prohibited by U.S., European or Japanese laws, including, without limitation, the development, design, manufacture or production of nuclear missiles, or any form of weapons.
  - summary: High-risk activities
    text: The Software covered by this subsection is not designed, manufactured or intended for use or resale as on-line control equipment in hazardous environments requiring fail-safe performance
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- RU
- BY
- CU
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Plesk
provenance_date: '2026-11-10'
provider_name: Plesk
provider_slug: plesk
slug: plesk-eligibility
source_date: '2026-11-10'
source_filename: plesk-eligibility.yml
source_heading: Eligibility
source_page: https://www.plesk.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plesk\naid: plesk\nurl: https://www.plesk.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  - CU\n  - IR\n  - KP\n  text: 'you are not located, organized or ordinarily resident in, and will not use or make available the Software,\n    including any AI Feature, in or to, the Russian Federation or Belarus. Also excluded: countries under comprehensive\n    sanctions or embargo, including Cuba, Iran, North Korea.'\nentity_types:\n- type: individual\n  text: a legal contract between you, as either an individual or an Entity (as defined below)\n- type:\
  \ business\n  text: IF YOU ARE ACCEPTING THIS AGREEMENT ON BEHALF OF A COMPANY, ORGANIZATION, EDUCATIONAL INSTITUTION, OR AGENCY\n- type: government\n  text: If the Software is acquired by or on behalf of an agency, department, or other entity of the U.S. Government\nrestricted_uses:\n- summary: Sanctioned jurisdictions and persons\n  text: neither you nor any End User to whom you make the Software available is listed on, or owned 50 percent or\n    more or controlled by one or more persons listed on, any sanctions list\n- summary: Weapons and prohibited end uses\n  text: You also agree that you will not use the Software for any purposes prohibited by U.S., European or Japanese\n    laws, including, without limitation, the development, design, manufacture or production of nuclear missiles,\n    or any form of weapons.\n- summary: High-risk activities\n  text: The Software covered by this subsection is not designed, manufactured or intended for use or resale as on-line\n    control equipment\
  \ in hazardous environments requiring fail-safe performance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/plesk/eligibility/plesk-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 7 quoted statements, read from Plesk's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Hosting
- Server Management
- Control Panel
- Automation
- WordPress
---
