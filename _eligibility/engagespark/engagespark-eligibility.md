---
api_specs:
- filename: engagespark-balance-api-openapi.yml
  format: yaml
  label: engageSPARK Balance API
  slug: engagespark-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-balance-api-openapi.yml
- filename: engagespark-campaigns-api-openapi.yml
  format: yaml
  label: engageSPARK Campaigns API
  slug: engagespark-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-campaigns-api-openapi.yml
- filename: engagespark-contacts-api-openapi.yml
  format: yaml
  label: engageSPARK Contacts API
  slug: engagespark-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-contacts-api-openapi.yml
- filename: engagespark-files-api-openapi.yml
  format: yaml
  label: engageSPARK Files API
  slug: engagespark-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-files-api-openapi.yml
- filename: engagespark-sms-api-openapi.yml
  format: yaml
  label: engageSPARK SMS API
  slug: engagespark-sms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-sms-api-openapi.yml
- filename: engagespark-top-up-api-openapi.yml
  format: yaml
  label: engageSPARK Top-Up API
  slug: engagespark-top-up-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-top-up-api-openapi.yml
- filename: engagespark-whats-app-api-openapi.yml
  format: yaml
  label: engageSPARK Whats App API
  slug: engagespark-whats-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engagespark/openapi/engagespark-whats-app-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be of legal age to form a binding contract with us according to the laws of your country
    type: individual
  - text: Have full legal authority to bind an entity to these Terms, if you are signing up for or using the Service on behalf of an entity
    type: business
  minimum_age:
    text: Be of legal age to form a binding contract with us according to the laws of your country
    value: null
  restricted_uses:
  - summary: HIPAA protected health information
    text: you may not use the Service to Process, electronic Protected Health Information (ePHI) within the meaning of the U.S. Health Insurance Portability and Accountability Act (HIPAA), unless you have first entered into a written Business Associate Agreement (BAA) with engageSPARK.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may refuse service, close accounts, and change eligibility requirements at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: engageSPARK
provenance_date: '2026-11-09'
provider_name: engageSPARK
provider_slug: engagespark
slug: engagespark-eligibility
source_date: '2026-11-09'
source_filename: engagespark-eligibility.yml
source_heading: Eligibility
source_page: https://www.engagespark.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: engageSPARK\naid: engagespark\nurl: https://www.engagespark.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be of legal age to form a binding contract with us according to the laws of your country\n- type: business\n  text: Have full legal authority to bind an entity to these Terms, if you are signing up for or using the Service\n    on behalf of an entity\nrestricted_uses:\n- summary: HIPAA protected health information\n  text: you may not use the Service to Process, electronic Protected Health Information\
  \ (ePHI) within the meaning\n    of the U.S. Health Insurance Portability and Accountability Act (HIPAA), unless you have first entered into\n    a written Business Associate Agreement (BAA) with engageSPARK.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may refuse service, close accounts, and change eligibility requirements at any time.\nminimum_age:\n  value: null\n  text: Be of legal age to form a binding contract with us according to the laws of your country\n"
source_yaml_url: https://artifacts.apis.io/engagespark/eligibility/engagespark-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from engageSPARK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Messaging
- SMS
- Voice
- WhatsApp
- Airtime
- Communications
- CPaaS
- Surveys
- International Development
---
