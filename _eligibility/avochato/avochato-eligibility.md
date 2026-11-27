---
api_specs:
- filename: avochato-avochato-api-api-openapi.yml
  format: yaml
  label: Avochato Avochato API
  slug: avochato-avochato-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avochato/openapi/avochato-avochato-api-api-openapi.yml
- filename: avochato-broadcasts-api-openapi.yml
  format: yaml
  label: Avochato Broadcasts API
  slug: avochato-broadcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avochato/openapi/avochato-broadcasts-api-openapi.yml
- filename: avochato-campaigns-api-openapi.yml
  format: yaml
  label: Avochato Campaigns API
  slug: avochato-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avochato/openapi/avochato-campaigns-api-openapi.yml
- filename: avochato-contacts-api-openapi.yml
  format: yaml
  label: Avochato Contacts API
  slug: avochato-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avochato/openapi/avochato-contacts-api-openapi.yml
- filename: avochato-links-api-openapi.yml
  format: yaml
  label: Avochato Links API
  slug: avochato-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avochato/openapi/avochato-links-api-openapi.yml
- filename: avochato-messages-api-openapi.yml
  format: yaml
  label: Avochato Messages API
  slug: avochato-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avochato/openapi/avochato-messages-api-openapi.yml
- filename: avochato-tickets-api-openapi.yml
  format: yaml
  label: Avochato Tickets API
  slug: avochato-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avochato/openapi/avochato-tickets-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You acknowledge that our Services are not intended for purchase by consumers and you represent and warrant that you will not register an Account for personal, family or household purposes.
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE COMPANY PROPERTIES OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Acceptable Use Policy and forbidden SMS categories
    text: that involve any activities delineated in our forbidden SMS and MMS categories policy , including but not limited to debt collection, gambling, casinos, overly ambitious investments, high risk financial services, cryptocurrency, payday loans, student loans, cannabis, CBD, fireworks, prescription drugs, alcohol, firearms, tobacco, third party lead generation services
  - summary: No emergency response systems without consent
    text: use, without the Company’s prior express written consent in each instance, the Company Properties to provision an emergency reporting or response system (e.g., Enhanced 911 or E911 emergency service)
  - summary: No life-critical systems
    text: to support the operation of a life support system, nuclear facility, aircraft navigation system, air traffic control system or other system critical to human life or safety
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
name: Avochato
provenance_date: '2026-11-09'
provider_name: Avochato
provider_slug: avochato
slug: avochato-eligibility
source_date: '2026-11-09'
source_filename: avochato-eligibility.yml
source_heading: Eligibility
source_page: https://www.avochato.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avochato\naid: avochato\nurl: https://www.avochato.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You acknowledge that our Services are not intended for purchase by consumers and you represent and warrant\n    that you will not register an Account for personal, family or household purposes.\nrestricted_uses:\n- summary: Acceptable Use Policy and forbidden SMS categories\n  text: that involve any activities delineated in our forbidden SMS and MMS categories policy , including but not\n    limited to debt\
  \ collection, gambling, casinos, overly ambitious investments, high risk financial services, cryptocurrency,\n    payday loans, student loans, cannabis, CBD, fireworks, prescription drugs, alcohol, firearms, tobacco, third\n    party lead generation services\n- summary: No emergency response systems without consent\n  text: use, without the Company’s prior express written consent in each instance, the Company Properties to provision\n    an emergency reporting or response system (e.g., Enhanced 911 or E911 emergency service)\n- summary: No life-critical systems\n  text: to support the operation of a life support system, nuclear facility, aircraft navigation system, air traffic\n    control system or other system critical to human life or safety\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE COMPANY PROPERTIES OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/avochato/eligibility/avochato-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Avochato's own page on 2026-11-09.
synthetic: false
tags:
- Messaging
- SMS
- RCS
- Voice
- Business
---
