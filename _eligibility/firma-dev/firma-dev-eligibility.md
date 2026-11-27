---
api_specs:
- filename: firma-dev-company-api-openapi.yml
  format: yaml
  label: Firma.dev Company API
  slug: firma-dev-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-company-api-openapi.yml
- filename: firma-dev-custom-fields-api-openapi.yml
  format: yaml
  label: Firma.dev Custom Fields API
  slug: firma-dev-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-custom-fields-api-openapi.yml
- filename: firma-dev-email-domains-api-openapi.yml
  format: yaml
  label: Firma.dev Email Domains API
  slug: firma-dev-email-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-email-domains-api-openapi.yml
- filename: firma-dev-email-templates-api-openapi.yml
  format: yaml
  label: Firma.dev Email Templates API
  slug: firma-dev-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-email-templates-api-openapi.yml
- filename: firma-dev-jwt-management-api-openapi.yml
  format: yaml
  label: Firma.dev JWT Management API
  slug: firma-dev-jwt-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-jwt-management-api-openapi.yml
- filename: firma-dev-organization-seals-api-openapi.yml
  format: yaml
  label: Firma.dev Organization Seals API
  slug: firma-dev-organization-seals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-organization-seals-api-openapi.yml
- filename: firma-dev-signer-terms-api-openapi.yml
  format: yaml
  label: Firma.dev Signer Terms API
  slug: firma-dev-signer-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-signer-terms-api-openapi.yml
- filename: firma-dev-signing-requests-api-openapi.yml
  format: yaml
  label: Firma.dev Signing Requests API
  slug: firma-dev-signing-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-signing-requests-api-openapi.yml
- filename: firma-dev-templates-api-openapi.yml
  format: yaml
  label: Firma.dev Templates API
  slug: firma-dev-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-templates-api-openapi.yml
- filename: firma-dev-webhooks-api-openapi.yml
  format: yaml
  label: Firma.dev Webhooks API
  slug: firma-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-webhooks-api-openapi.yml
- filename: firma-dev-workspace-settings-api-openapi.yml
  format: yaml
  label: Firma.dev Workspace Settings API
  slug: firma-dev-workspace-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-workspace-settings-api-openapi.yml
- filename: firma-dev-workspaces-api-openapi.yml
  format: yaml
  label: Firma.dev Workspaces API
  slug: firma-dev-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/firma-dev/openapi/firma-dev-workspaces-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A business entity that purchases and uses credits to access the Service.
    type: business
  - text: any individual who views, reviews, or electronically signs a document (“Signer”) through Firma’s Service
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or deceptive documents
    text: send documents or content that are unlawful, fraudulent, deceptive or defamatory, or that infringe anyone’s rights
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
name: Firma.dev
provenance_date: '2026-11-09'
provider_name: Firma.dev
provider_slug: firma-dev
slug: firma-dev-eligibility
source_date: '2026-11-09'
source_filename: firma-dev-eligibility.yml
source_heading: Eligibility
source_page: https://firma.dev/legal/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Firma.dev\naid: firma-dev\nurl: https://firma.dev/legal/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: A business entity that purchases and uses credits to access the Service.\n- type: individual\n  text: any individual who views, reviews, or electronically signs a document (“Signer”) through Firma’s Service\nrestricted_uses:\n- summary: Unlawful or deceptive documents\n  text: send documents or content that are unlawful, fraudulent, deceptive or defamatory, or that infringe anyone’s\n    rights\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/firma-dev/eligibility/firma-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Firma.dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Signature
- Developer Tools
- LowCost
---
