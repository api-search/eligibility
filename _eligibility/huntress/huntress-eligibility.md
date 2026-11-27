---
api_specs:
- filename: huntress-accounts-api-openapi.yml
  format: yaml
  label: Huntress Accounts API
  slug: huntress-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-accounts-api-openapi.yml
- filename: huntress-actor-api-openapi.yml
  format: yaml
  label: Huntress Actor API
  slug: huntress-actor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-actor-api-openapi.yml
- filename: huntress-agents-api-openapi.yml
  format: yaml
  label: Huntress Agents API
  slug: huntress-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-agents-api-openapi.yml
- filename: huntress-escalations-api-openapi.yml
  format: yaml
  label: Huntress Escalations API
  slug: huntress-escalations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-escalations-api-openapi.yml
- filename: huntress-external-recon-api-openapi.yml
  format: yaml
  label: Huntress External Recon API
  slug: huntress-external-recon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-external-recon-api-openapi.yml
- filename: huntress-identities-api-openapi.yml
  format: yaml
  label: Huntress Identities API
  slug: huntress-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-identities-api-openapi.yml
- filename: huntress-incident-reports-api-openapi.yml
  format: yaml
  label: Huntress Incident Reports API
  slug: huntress-incident-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-incident-reports-api-openapi.yml
- filename: huntress-invoices-api-openapi.yml
  format: yaml
  label: Huntress Invoices API
  slug: huntress-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-invoices-api-openapi.yml
- filename: huntress-known-vpns-api-openapi.yml
  format: yaml
  label: Huntress Known VPNs API
  slug: huntress-known-vpns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-known-vpns-api-openapi.yml
- filename: huntress-organizations-api-openapi.yml
  format: yaml
  label: Huntress Organizations API
  slug: huntress-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-organizations-api-openapi.yml
- filename: huntress-platform-actions-api-openapi.yml
  format: yaml
  label: Huntress Platform Actions API
  slug: huntress-platform-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-platform-actions-api-openapi.yml
- filename: huntress-reseller-api-openapi.yml
  format: yaml
  label: Huntress Reseller API
  slug: huntress-reseller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-reseller-api-openapi.yml
- filename: huntress-siem-api-openapi.yml
  format: yaml
  label: Huntress SIEM API
  slug: huntress-siem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-siem-api-openapi.yml
- filename: huntress-signals-api-openapi.yml
  format: yaml
  label: Huntress Signals API
  slug: huntress-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-signals-api-openapi.yml
- filename: huntress-summary-reports-api-openapi.yml
  format: yaml
  label: Huntress Summary Reports API
  slug: huntress-summary-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-summary-reports-api-openapi.yml
- filename: huntress-unwanted-access-rules-api-openapi.yml
  format: yaml
  label: Huntress Unwanted Access Rules API
  slug: huntress-unwanted-access-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-unwanted-access-rules-api-openapi.yml
- filename: huntress-users-api-openapi.yml
  format: yaml
  label: Huntress Users API
  slug: huntress-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/huntress/openapi/huntress-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Company, or any products utilizing such data, in violation of the United States export laws or regulations.
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
name: Huntress
provenance_date: '2026-11-09'
provider_name: Huntress
provider_slug: huntress
slug: huntress-eligibility
source_date: '2026-11-09'
source_filename: huntress-eligibility.yml
source_heading: Eligibility
source_page: https://www.huntress.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Huntress\naid: huntress\nurl: https://www.huntress.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export restrictions\n  text: You agree not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired\n    from Company, or any products utilizing such data, in violation of the United States export laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT\
  \ THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/huntress/eligibility/huntress-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Huntress's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Managed Detection and Response
- Endpoint Security
- SOC
- SIEM
- Identity Threat Detection
- MSP
- Webhook
---
