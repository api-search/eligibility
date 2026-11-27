---
api_specs:
- filename: ahasend-accounts-api-openapi.yml
  format: yaml
  label: AhaSend Accounts API
  slug: ahasend-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-accounts-api-openapi.yml
- filename: ahasend-api-keys-api-openapi.yml
  format: yaml
  label: AhaSend API Keys API
  slug: ahasend-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-api-keys-api-openapi.yml
- filename: ahasend-domains-api-openapi.yml
  format: yaml
  label: AhaSend Domains API
  slug: ahasend-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-domains-api-openapi.yml
- filename: ahasend-email-api-openapi.yml
  format: yaml
  label: AhaSend Email API
  slug: ahasend-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-email-api-openapi.yml
- filename: ahasend-messages-api-openapi.yml
  format: yaml
  label: AhaSend Messages API
  slug: ahasend-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-messages-api-openapi.yml
- filename: ahasend-routes-api-openapi.yml
  format: yaml
  label: AhaSend Routes API
  slug: ahasend-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-routes-api-openapi.yml
- filename: ahasend-smtp-credentials-api-openapi.yml
  format: yaml
  label: AhaSend SMTP Credentials API
  slug: ahasend-smtp-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-smtp-credentials-api-openapi.yml
- filename: ahasend-statistics-api-openapi.yml
  format: yaml
  label: AhaSend Statistics API
  slug: ahasend-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-statistics-api-openapi.yml
- filename: ahasend-suppressions-api-openapi.yml
  format: yaml
  label: AhaSend Suppressions API
  slug: ahasend-suppressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-suppressions-api-openapi.yml
- filename: ahasend-utility-api-openapi.yml
  format: yaml
  label: AhaSend Utility API
  slug: ahasend-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-utility-api-openapi.yml
- filename: ahasend-webhooks-api-openapi.yml
  format: yaml
  label: AhaSend Webhooks API
  slug: ahasend-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-webhooks-api-openapi.yml
- filename: ahasend-campaign-templates-api-openapi.yml
  format: yaml
  label: AhaSend Campaign Templates API
  slug: ahasend-campaign-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-campaign-templates-api-openapi.yml
- filename: ahasend-campaigns-api-openapi.yml
  format: yaml
  label: AhaSend Campaigns API
  slug: ahasend-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-campaigns-api-openapi.yml
- filename: ahasend-contacts-api-openapi.yml
  format: yaml
  label: AhaSend Contacts API
  slug: ahasend-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-contacts-api-openapi.yml
- filename: ahasend-lists-api-openapi.yml
  format: yaml
  label: AhaSend Lists API
  slug: ahasend-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-lists-api-openapi.yml
- filename: ahasend-templates-api-openapi.yml
  format: yaml
  label: AhaSend Templates API
  slug: ahasend-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-templates-api-openapi.yml
- filename: ahasend-subaccounts-api-openapi.yml
  format: yaml
  label: AhaSend Subaccounts API
  slug: ahasend-subaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-subaccounts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Gambling
    text: 'Gambling: Any promotion of online casinos, sports betting, lottery schemes, or unlicensed gambling activities.'
  - summary: Adult content
    text: 'Adult Content: Explicit sexual material, pornography, escort services, or sexually oriented products/services not suitable for a general audience.'
  - summary: Unlicensed cryptocurrency promotion
    text: 'Unlicensed Cryptocurrencies and trading platforms: Promotion of cryptocurrency investments, initial coin offerings (ICOs), or unlicensed crypto trading platforms.'
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
name: AhaSend
provenance_date: '2026-11-09'
provider_name: AhaSend
provider_slug: ahasend
slug: ahasend-eligibility
source_date: '2026-11-09'
source_filename: ahasend-eligibility.yml
source_heading: Eligibility
source_page: https://ahasend.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AhaSend\naid: ahasend\nurl: https://ahasend.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you are agreeing to these Terms for that organization\nrestricted_uses:\n- summary: Gambling\n  text: 'Gambling: Any promotion of online casinos, sports betting, lottery schemes, or unlicensed gambling activities.'\n- summary: Adult content\n  text: 'Adult Content: Explicit sexual material, pornography, escort services, or sexually oriented products/services\n    not suitable\
  \ for a general audience.'\n- summary: Unlicensed cryptocurrency promotion\n  text: 'Unlicensed Cryptocurrencies and trading platforms: Promotion of cryptocurrency investments, initial coin\n    offerings (ICOs), or unlicensed crypto trading platforms.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ahasend/eligibility/ahasend-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from AhaSend's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Transactional Email
- Developer Tools
- SMTP
- Webhook
---
