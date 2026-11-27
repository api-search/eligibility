---
api_specs:
- filename: sanctionskit-batches-and-files-api-openapi.yml
  format: yaml
  label: SanctionsKit Batches and files API
  slug: sanctionskit-batches-and-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-batches-and-files-api-openapi.yml
- filename: sanctionskit-counterparties-api-openapi.yml
  format: yaml
  label: SanctionsKit Counterparties API
  slug: sanctionskit-counterparties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-counterparties-api-openapi.yml
- filename: sanctionskit-monitoring-api-openapi.yml
  format: yaml
  label: SanctionsKit Monitoring API
  slug: sanctionskit-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-monitoring-api-openapi.yml
- filename: sanctionskit-reports-api-openapi.yml
  format: yaml
  label: SanctionsKit Reports API
  slug: sanctionskit-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-reports-api-openapi.yml
- filename: sanctionskit-review-evidence-api-openapi.yml
  format: yaml
  label: SanctionsKit Review evidence API
  slug: sanctionskit-review-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-review-evidence-api-openapi.yml
- filename: sanctionskit-screening-and-evidence-api-openapi.yml
  format: yaml
  label: SanctionsKit Screening and evidence API
  slug: sanctionskit-screening-and-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-screening-and-evidence-api-openapi.yml
- filename: sanctionskit-screening-policies-api-openapi.yml
  format: yaml
  label: SanctionsKit Screening policies API
  slug: sanctionskit-screening-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-screening-policies-api-openapi.yml
- filename: sanctionskit-source-discovery-api-openapi.yml
  format: yaml
  label: SanctionsKit Source discovery API
  slug: sanctionskit-source-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-source-discovery-api-openapi.yml
- filename: sanctionskit-usage-api-openapi.yml
  format: yaml
  label: SanctionsKit Usage API
  slug: sanctionskit-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-usage-api-openapi.yml
- filename: sanctionskit-webhooks-api-openapi.yml
  format: yaml
  label: SanctionsKit Webhooks API
  slug: sanctionskit-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sanctionskit/openapi/sanctionskit-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not access or supply the Services where doing so is prohibited by applicable sanctions or export-control law, and may not make them available to a prohibited recipient.
  entity_types:
  - text: The Services are intended for business and professional use, rather than personal, family, or household purchases.
    type: business
  minimum_age:
    text: Authorized Users must be at least 18 and have legal capacity to enter an agreement.
    value: '18'
  restricted_uses:
  - summary: No FCRA consumer-report use
    text: You must not use the Services or results to determine an individual’s eligibility for credit, insurance, employment, housing, or another purpose that would require a consumer report under the FCRA or analogous law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may verify your identity, organization, authority, and eligibility where reasonably needed to administer or secure the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SanctionsKit
provenance_date: '2026-11-10'
provider_name: SanctionsKit
provider_slug: sanctionskit
slug: sanctionskit-eligibility
source_date: '2026-11-10'
source_filename: sanctionskit-eligibility.yml
source_heading: Eligibility
source_page: https://www.sanctionskit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SanctionsKit\naid: sanctionskit\nurl: https://www.sanctionskit.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not access or supply the Services where doing so is prohibited by applicable sanctions or export-control\n    law, and may not make them available to a prohibited recipient.\nentity_types:\n- type: business\n  text: The Services are intended for business and professional use, rather than personal, family, or household\n    purchases.\nrestricted_uses:\n- summary: No FCRA consumer-report use\n  text: You must not use the Services or results to determine\
  \ an individual’s eligibility for credit, insurance,\n    employment, housing, or another purpose that would require a consumer report under the FCRA or analogous law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may verify your identity, organization, authority, and eligibility where reasonably needed to administer\n    or secure the Services.\nminimum_age:\n  value: '18'\n  text: Authorized Users must be at least 18 and have legal capacity to enter an agreement.\n"
source_yaml_url: https://artifacts.apis.io/sanctionskit/eligibility/sanctionskit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from SanctionsKit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sanctions
- Compliance
- Screening
- Fintech
---
