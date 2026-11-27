---
api_specs:
- filename: hunter-account-api-openapi.yml
  format: yaml
  label: Hunter Account API
  slug: hunter-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-account-api-openapi.yml
- filename: hunter-campaigns-api-openapi.yml
  format: yaml
  label: Hunter Campaigns API
  slug: hunter-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-campaigns-api-openapi.yml
- filename: hunter-discover-api-openapi.yml
  format: yaml
  label: Hunter Discover API
  slug: hunter-discover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-discover-api-openapi.yml
- filename: hunter-leads-api-openapi.yml
  format: yaml
  label: Hunter Leads API
  slug: hunter-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-leads-api-openapi.yml
- filename: hunter-api-keys-api-openapi.yml
  format: yaml
  label: Hunter API Keys API
  slug: hunter-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-api-keys-api-openapi.yml
- filename: hunter-companies-api-openapi.yml
  format: yaml
  label: Hunter Companies API
  slug: hunter-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-companies-api-openapi.yml
- filename: hunter-connected-apps-api-openapi.yml
  format: yaml
  label: Hunter Connected Apps API
  slug: hunter-connected-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-connected-apps-api-openapi.yml
- filename: hunter-email-accounts-api-openapi.yml
  format: yaml
  label: Hunter Email Accounts API
  slug: hunter-email-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-email-accounts-api-openapi.yml
- filename: hunter-enrichment-api-openapi.yml
  format: yaml
  label: Hunter Enrichment API
  slug: hunter-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-enrichment-api-openapi.yml
- filename: hunter-feedback-api-openapi.yml
  format: yaml
  label: Hunter Feedback API
  slug: hunter-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-feedback-api-openapi.yml
- filename: hunter-finder-api-openapi.yml
  format: yaml
  label: Hunter Finder API
  slug: hunter-finder-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-finder-api-openapi.yml
- filename: hunter-lists-api-openapi.yml
  format: yaml
  label: Hunter Lists API
  slug: hunter-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-lists-api-openapi.yml
- filename: hunter-messages-api-openapi.yml
  format: yaml
  label: Hunter Messages API
  slug: hunter-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-messages-api-openapi.yml
- filename: hunter-multi-domain-search-api-openapi.yml
  format: yaml
  label: Hunter Multi-Domain Search API
  slug: hunter-multi-domain-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-multi-domain-search-api-openapi.yml
- filename: hunter-sequences-api-openapi.yml
  format: yaml
  label: Hunter Sequences API
  slug: hunter-sequences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-sequences-api-openapi.yml
- filename: hunter-tags-api-openapi.yml
  format: yaml
  label: Hunter Tags API
  slug: hunter-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-tags-api-openapi.yml
- filename: hunter-team-api-openapi.yml
  format: yaml
  label: Hunter Team API
  slug: hunter-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-team-api-openapi.yml
- filename: hunter-templates-api-openapi.yml
  format: yaml
  label: Hunter Templates API
  slug: hunter-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-templates-api-openapi.yml
- filename: hunter-usage-api-openapi.yml
  format: yaml
  label: Hunter Usage API
  slug: hunter-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-usage-api-openapi.yml
- filename: hunter-verifier-api-openapi.yml
  format: yaml
  label: Hunter Verifier API
  slug: hunter-verifier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-verifier-api-openapi.yml
- filename: hunter-views-api-openapi.yml
  format: yaml
  label: Hunter Views API
  slug: hunter-views-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-views-api-openapi.yml
- filename: hunter-webhooks-api-openapi.yml
  format: yaml
  label: Hunter Webhooks API
  slug: hunter-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunter/openapi/hunter-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Additional terms apply exclusively to India residents and businesses incorporated in India.
  entity_types:
  - text: The Services are available only to individuals who are at least 18 years old.
    type: individual
  - text: Paid plans or products on Hunter are only available to businesses. Consumers should not attempt to perform a purchase on Hunter.
    type: business
  minimum_age:
    text: The Services are available only to individuals who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Impersonation
    text: Impersonate or attempt to impersonate Hunter, a Hunter employee, another user, or any other person or entity
  - summary: Exploiting minors
    text: Exploit, harm, or attempt to exploit or harm minors in any way
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
name: Hunter
provenance_date: '2026-11-09'
provider_name: Hunter
provider_slug: hunter
slug: hunter-eligibility
source_date: '2026-11-09'
source_filename: hunter-eligibility.yml
source_heading: Eligibility
source_page: https://hunter.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hunter\naid: hunter\nurl: https://hunter.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Additional terms apply exclusively to India residents and businesses incorporated in India.\nentity_types:\n- type: individual\n  text: The Services are available only to individuals who are at least 18 years old.\n- type: business\n  text: Paid plans or products on Hunter are only available to businesses. Consumers should not attempt to perform\n    a purchase on Hunter.\nrestricted_uses:\n- summary: Impersonation\n  text: Impersonate or attempt to impersonate Hunter, a Hunter\
  \ employee, another user, or any other person or entity\n- summary: Exploiting minors\n  text: Exploit, harm, or attempt to exploit or harm minors in any way\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are available only to individuals who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/hunter/eligibility/hunter-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Hunter's own page on 2026-11-09.
synthetic: false
tags:
- Contact Discovery
- Email
- Email Verification
- Lead Generation
- Prospecting
- Sales Intelligence
---
