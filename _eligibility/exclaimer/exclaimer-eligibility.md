---
api_specs:
- filename: exclaimer-end-users-api-openapi.yml
  format: yaml
  label: Exclaimer End Users API
  slug: exclaimer-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-end-users-api-openapi.yml
- filename: exclaimer-mailboxes-api-openapi.yml
  format: yaml
  label: Exclaimer Mailboxes API
  slug: exclaimer-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-mailboxes-api-openapi.yml
- filename: exclaimer-miscellaneous-api-openapi.yml
  format: yaml
  label: Exclaimer Miscellaneous API
  slug: exclaimer-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-miscellaneous-api-openapi.yml
- filename: exclaimer-msp-api-openapi.yml
  format: yaml
  label: Exclaimer MSP API
  slug: exclaimer-msp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-msp-api-openapi.yml
- filename: exclaimer-reference-resources-api-openapi.yml
  format: yaml
  label: Exclaimer Reference Resources API
  slug: exclaimer-reference-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-reference-resources-api-openapi.yml
- filename: exclaimer-resellers-api-openapi.yml
  format: yaml
  label: Exclaimer Resellers API
  slug: exclaimer-resellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-resellers-api-openapi.yml
- filename: exclaimer-subscription-transfers-api-openapi.yml
  format: yaml
  label: Exclaimer Subscription Transfers API
  slug: exclaimer-subscription-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-subscription-transfers-api-openapi.yml
- filename: exclaimer-subscription-users-api-openapi.yml
  format: yaml
  label: Exclaimer Subscription Users API
  slug: exclaimer-subscription-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-subscription-users-api-openapi.yml
- filename: exclaimer-subscriptions-api-openapi.yml
  format: yaml
  label: Exclaimer Subscriptions API
  slug: exclaimer-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-subscriptions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Business use only
    text: These platforms are for business users only. We have no liability to anyone using them for personal or consumer purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to the Portal requires a valid partner account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Exclaimer
provenance_date: '2026-11-09'
provider_name: Exclaimer
provider_slug: exclaimer
slug: exclaimer-eligibility
source_date: '2026-11-09'
source_filename: exclaimer-eligibility.yml
source_heading: Eligibility
source_page: https://exclaimer.com/legal/website-terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Exclaimer\naid: exclaimer\nurl: https://exclaimer.com/legal/website-terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Business use only\n  text: These platforms are for business users only. We have no liability to anyone using them for personal or consumer\n    purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to the Portal requires a valid partner account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/exclaimer/eligibility/exclaimer-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Exclaimer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Email Signatures
- Email Signature Management
- Microsoft 365
- Google Workspace
- Marketing
- Productivity
- Software-as-a-Service
- Security
---
