---
api_specs:
- filename: krosyn-connectors-api-openapi.yml
  format: yaml
  label: Chmura Software Connectors API
  slug: krosyn-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/krosyn/openapi/krosyn-connectors-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You represent and warrant that you are not located in, organized under the laws of, or a resident of any country or territory subject to comprehensive trade sanctions by the European Union or the United States (including, as of the date of these Terms, Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine)
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have the authority to bind that organization to these Terms
    type: business
  - text: If you are under 18 , you may use the Free plan, but you may only take out a paid subscription or buy AI credits with the consent of a parent or guardian
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Illegal or harmful use
    text: Use the Service to facilitate fraud, money laundering, financing of terrorism, or other criminal activity
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
name: Chmura Software
provenance_date: '2026-11-09'
provider_name: Chmura Software
provider_slug: krosyn
slug: krosyn-eligibility
source_date: '2026-11-09'
source_filename: krosyn-eligibility.yml
source_heading: Eligibility
source_page: https://krosyn.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chmura Software\naid: krosyn\nurl: https://krosyn.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You represent and warrant that you are not located in, organized under the laws of, or a resident of any\n    country or territory subject to comprehensive trade sanctions by the European Union or the United States (including,\n    as of the date of these Terms, Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions\n    of Ukraine)\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization,\
  \ you represent that you have the authority to\n    bind that organization to these Terms\n- type: individual\n  text: If you are under 18 , you may use the Free plan, but you may only take out a paid subscription or buy AI\n    credits with the consent of a parent or guardian\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: Use the Service to facilitate fraud, money laundering, financing of terrorism, or other criminal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/krosyn/eligibility/krosyn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Chmura Software's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Developer Tools
- Security
---
