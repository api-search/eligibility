---
api_specs:
- filename: precoro-openapi-generated.yml
  format: yaml
  label: Precoro API
  slug: precoro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/_ae-authored/precoro-openapi-generated.yml
- filename: precoro-invoices-api-openapi.yml
  format: yaml
  label: Precoro Invoices API
  slug: precoro-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-invoices-api-openapi.yml
- filename: precoro-items-api-openapi.yml
  format: yaml
  label: Precoro Items API
  slug: precoro-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-items-api-openapi.yml
- filename: precoro-legalentities-api-openapi.yml
  format: yaml
  label: Precoro Legalentities API
  slug: precoro-legalentities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-legalentities-api-openapi.yml
- filename: precoro-locations-api-openapi.yml
  format: yaml
  label: Precoro Locations API
  slug: precoro-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-locations-api-openapi.yml
- filename: precoro-purchaseorders-api-openapi.yml
  format: yaml
  label: Precoro Purchaseorders API
  slug: precoro-purchaseorders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-purchaseorders-api-openapi.yml
- filename: precoro-purchaserequisitions-api-openapi.yml
  format: yaml
  label: Precoro Purchaserequisitions API
  slug: precoro-purchaserequisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-purchaserequisitions-api-openapi.yml
- filename: precoro-receipts-api-openapi.yml
  format: yaml
  label: Precoro Receipts API
  slug: precoro-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-receipts-api-openapi.yml
- filename: precoro-suppliers-api-openapi.yml
  format: yaml
  label: Precoro Suppliers API
  slug: precoro-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-suppliers-api-openapi.yml
- filename: precoro-taxes-api-openapi.yml
  format: yaml
  label: Precoro Taxes API
  slug: precoro-taxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precoro/openapi/precoro-taxes-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Customer" means a legal entity whose Users visit, browse, access, download, install, or otherwise use the Platform.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misuse
    text: '"Misuse" means any use of the Services that causes or is reasonably likely to cause financial, operational, legal, reputational, or security harm to Precoro'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Precoro may request information, documentation, certifications, beneficial ownership details, or other materials necessary to conduct compliance, sanctions, know-your-customer (KYC)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Precoro
provenance_date: '2026-11-10'
provider_name: Precoro
provider_slug: precoro
slug: precoro-eligibility
source_date: '2026-11-10'
source_filename: precoro-eligibility.yml
source_heading: Eligibility
source_page: https://precoro.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Precoro\naid: precoro\nurl: https://precoro.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"Customer\" means a legal entity whose Users visit, browse, access, download, install, or otherwise use\n    the Platform.'\nrestricted_uses:\n- summary: Misuse\n  text: '\"Misuse\" means any use of the Services that causes or is reasonably likely to cause financial, operational,\n    legal, reputational, or security harm to Precoro'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Precoro\
  \ may request information, documentation, certifications, beneficial ownership details, or other materials\n    necessary to conduct compliance, sanctions, know-your-customer (KYC)\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/precoro/eligibility/precoro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Precoro's own page on 2026-11-10.
synthetic: false
tags:
- Procurement
- Spend Management
- Vendor Management
- Purchase-To-Pay
- AP Automation
- Contract Management
- AI Procurement
---
