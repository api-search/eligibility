---
api_specs:
- filename: enrich-so-email-finder-api-openapi.yml
  format: yaml
  label: Enrich Email Finder API
  slug: enrich-so-email-finder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-email-finder-api-openapi.yml
- filename: enrich-so-lead-finder-api-openapi.yml
  format: yaml
  label: Enrich Lead Finder API
  slug: enrich-so-lead-finder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-lead-finder-api-openapi.yml
- filename: enrich-so-phone-finder-api-openapi.yml
  format: yaml
  label: Enrich Phone Finder API
  slug: enrich-so-phone-finder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-phone-finder-api-openapi.yml
- filename: enrich-so-teams-api-openapi.yml
  format: yaml
  label: Enrich Teams API
  slug: enrich-so-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-teams-api-openapi.yml
- filename: enrich-so-people-search-api-openapi.yml
  format: yaml
  label: Enrich People Search API
  slug: enrich-so-people-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-people-search-api-openapi.yml
- filename: enrich-so-authentication-api-openapi.yml
  format: yaml
  label: Enrich Authentication API
  slug: enrich-so-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-authentication-api-openapi.yml
- filename: enrich-so-company-followers-api-openapi.yml
  format: yaml
  label: Enrich Company Followers API
  slug: enrich-so-company-followers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-company-followers-api-openapi.yml
- filename: enrich-so-company-followers-count-estimation-api-openapi.yml
  format: yaml
  label: Enrich Company Followers/Count Estimation API
  slug: enrich-so-company-followers-count-estimation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-company-followers-count-estimation-api-openapi.yml
- filename: enrich-so-email-validation-api-openapi.yml
  format: yaml
  label: Enrich Email Validation API
  slug: enrich-so-email-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-email-validation-api-openapi.yml
- filename: enrich-so-enrich-api-openapi.yml
  format: yaml
  label: Enrich API
  slug: enrich-so-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-enrich-api-openapi.yml
- filename: enrich-so-ip-to-company-api-openapi.yml
  format: yaml
  label: Enrich IP to Company API
  slug: enrich-so-ip-to-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-ip-to-company-api-openapi.yml
- filename: enrich-so-reverse-email-lookup-api-openapi.yml
  format: yaml
  label: Enrich Reverse Email Lookup API
  slug: enrich-so-reverse-email-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-reverse-email-lookup-api-openapi.yml
- filename: enrich-so-wallets-api-openapi.yml
  format: yaml
  label: Enrich Wallets API
  slug: enrich-so-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-wallets-api-openapi.yml
- filename: enrich-so-account-api-openapi.yml
  format: yaml
  label: Enrich Account API
  slug: enrich-so-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-account-api-openapi.yml
- filename: enrich-so-company-intelligence-api-openapi.yml
  format: yaml
  label: Enrich Company Intelligence API
  slug: enrich-so-company-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-company-intelligence-api-openapi.yml
- filename: enrich-so-email-verification-api-openapi.yml
  format: yaml
  label: Enrich Email Verification API
  slug: enrich-so-email-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-email-verification-api-openapi.yml
- filename: enrich-so-person-enrichment-api-openapi.yml
  format: yaml
  label: Enrich Person Enrichment API
  slug: enrich-so-person-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-person-enrichment-api-openapi.yml
- filename: enrich-so-webhooks-api-openapi.yml
  format: yaml
  label: Enrich Webhooks API
  slug: enrich-so-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enrich-so/openapi/enrich-so-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU'RE AGREEING TO THESE TERMS ON BEHALF OF AN ORGANIZATION, YOU REPRESENT AND WARRANT THAT YOU ARE AUTHORIZED TO AGREE TO THESE TERMS ON THAT ORGANIZATION'S BEHALF
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, fraudulent or malicious use
    text: When using Enrich.so, users must not engage in any activities that are illegal, fraudulent, or malicious.
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
name: Enrich
provenance_date: '2026-11-09'
provider_name: Enrich
provider_slug: enrich-so
slug: enrich-so-eligibility
source_date: '2026-11-09'
source_filename: enrich-so-eligibility.yml
source_heading: Eligibility
source_page: https://www.enrich.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enrich\naid: enrich-so\nurl: https://www.enrich.so/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU'RE AGREEING TO THESE TERMS ON BEHALF OF AN ORGANIZATION, YOU REPRESENT AND WARRANT THAT YOU ARE AUTHORIZED\n    TO AGREE TO THESE TERMS ON THAT ORGANIZATION'S BEHALF\nrestricted_uses:\n- summary: Illegal, fraudulent or malicious use\n  text: When using Enrich.so, users must not engage in any activities that are illegal, fraudulent, or malicious.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enrich-so/eligibility/enrich-so-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Enrich's own page on 2026-11-09.
synthetic: false
tags:
- Data Enrichment
- Contact Discovery
- Web Intelligence
- B2B Data
- Lead Enrichment
- Email Finder
- Email Verification
- Phone Numbers
- People Search
- IP Intelligence
- LinkedIn
- Reference Data
- MCP
---
