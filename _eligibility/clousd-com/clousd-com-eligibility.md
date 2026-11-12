---
api_specs:
- filename: clousd-com-account-api-openapi.yml
  format: yaml
  label: Clousd Account API
  slug: clousd-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-account-api-openapi.yml
- filename: clousd-com-adb-api-openapi.yml
  format: yaml
  label: Clousd ADB API
  slug: clousd-com-adb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-adb-api-openapi.yml
- filename: clousd-com-ai-agents-api-openapi.yml
  format: yaml
  label: Clousd AI agents API
  slug: clousd-com-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-ai-agents-api-openapi.yml
- filename: clousd-com-apps-api-openapi.yml
  format: yaml
  label: Clousd Apps API
  slug: clousd-com-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-apps-api-openapi.yml
- filename: clousd-com-devices-api-openapi.yml
  format: yaml
  label: Clousd Devices API
  slug: clousd-com-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-devices-api-openapi.yml
- filename: clousd-com-files-and-media-api-openapi.yml
  format: yaml
  label: Clousd Files and media API
  slug: clousd-com-files-and-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-files-and-media-api-openapi.yml
- filename: clousd-com-network-api-openapi.yml
  format: yaml
  label: Clousd Network API
  slug: clousd-com-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-network-api-openapi.yml
- filename: clousd-com-screen-and-input-api-openapi.yml
  format: yaml
  label: Clousd Screen and input API
  slug: clousd-com-screen-and-input-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-screen-and-input-api-openapi.yml
- filename: clousd-com-tasks-api-openapi.yml
  format: yaml
  label: Clousd Tasks API
  slug: clousd-com-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-tasks-api-openapi.yml
- filename: clousd-com-webhooks-api-openapi.yml
  format: yaml
  label: Clousd Webhooks API
  slug: clousd-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clousd-com/openapi/clousd-com-webhooks-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    - BY
    served: []
    text: We do not offer the service in the countries listed in section 16, and sign-ups from those countries are declined. ... currently Cuba, Iran, North Korea, Syria, and the Crimea, so-called Donetsk and Luhansk regions of Ukraine
  entity_types:
  - text: You must be at least 18 years old (or the age of majority where you live, if higher) and able to enter into a binding contract.
    type: individual
  - text: The service is intended primarily for business and professional use
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority where you live, if higher)
    value: '18'
  restricted_uses:
  - summary: Sanctions and export restrictions
    text: You represent that you are not located in, ordinarily resident in, or organized under the laws of a country or region subject to comprehensive sanctions
  - summary: Fraud and unauthorized access
    text: no fraud, no spam, no fake engagement, no evading bans, limits or protections set by other services, no unauthorized access
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may ask you to verify your identity, your organization, the purpose of your use or the source of a payment
excluded_countries:
- CU
- IR
- KP
- SY
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clousd
provenance_date: '2026-11-09'
provider_name: Clousd
provider_slug: clousd-com
slug: clousd-com-eligibility
source_date: '2026-11-09'
source_filename: clousd-com-eligibility.yml
source_heading: Eligibility
source_page: https://clousd.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clousd\naid: clousd-com\nurl: https://clousd.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  - BY\n  text: We do not offer the service in the countries listed in section 16, and sign-ups from those countries are\n    declined. ... currently Cuba, Iran, North Korea, Syria, and the Crimea, so-called Donetsk and Luhansk regions\n    of Ukraine\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority where you live, if higher) and able to enter into\n    a binding contract.\n- type: business\n  text:\
  \ The service is intended primarily for business and professional use\nrestricted_uses:\n- summary: Sanctions and export restrictions\n  text: You represent that you are not located in, ordinarily resident in, or organized under the laws of a country\n    or region subject to comprehensive sanctions\n- summary: Fraud and unauthorized access\n  text: no fraud, no spam, no fake engagement, no evading bans, limits or protections set by other services, no\n    unauthorized access\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may ask you to verify your identity, your organization, the purpose of your use or the source of a payment\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority where you live, if higher)\n"
source_yaml_url: https://artifacts.apis.io/clousd-com/eligibility/clousd-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Clousd's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Android
- Cloud Phones
- AI Agents
- MCP
- Mobile Testing
- QA
- Emulators
---
