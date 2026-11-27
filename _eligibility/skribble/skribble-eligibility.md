---
api_specs:
- filename: skribble-access-api-openapi.yml
  format: yaml
  label: Skribble Access API
  slug: skribble-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-access-api-openapi.yml
- filename: skribble-additional-information-api-openapi.yml
  format: yaml
  label: Skribble Additional Information API
  slug: skribble-additional-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-additional-information-api-openapi.yml
- filename: skribble-billing-and-credits-api-openapi.yml
  format: yaml
  label: Skribble Billing and Credits API
  slug: skribble-billing-and-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-billing-and-credits-api-openapi.yml
- filename: skribble-document-api-openapi.yml
  format: yaml
  label: Skribble Document API
  slug: skribble-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-document-api-openapi.yml
- filename: skribble-identification-api-openapi.yml
  format: yaml
  label: Skribble Identification API
  slug: skribble-identification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-identification-api-openapi.yml
- filename: skribble-monitoring-api-openapi.yml
  format: yaml
  label: Skribble Monitoring API
  slug: skribble-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-monitoring-api-openapi.yml
- filename: skribble-report-api-openapi.yml
  format: yaml
  label: Skribble Report API
  slug: skribble-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-report-api-openapi.yml
- filename: skribble-reports-api-openapi.yml
  format: yaml
  label: Skribble Reports API
  slug: skribble-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-reports-api-openapi.yml
- filename: skribble-seal-api-openapi.yml
  format: yaml
  label: Skribble Seal API
  slug: skribble-seal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-seal-api-openapi.yml
- filename: skribble-sendto-api-openapi.yml
  format: yaml
  label: Skribble Send To API
  slug: skribble-sendto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-sendto-api-openapi.yml
- filename: skribble-signature-api-openapi.yml
  format: yaml
  label: Skribble Signature API
  slug: skribble-signature-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-signature-api-openapi.yml
- filename: skribble-signature-attachment-api-openapi.yml
  format: yaml
  label: Skribble Signature Attachment API
  slug: skribble-signature-attachment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-signature-attachment-api-openapi.yml
- filename: skribble-signature-handling-api-openapi.yml
  format: yaml
  label: Skribble Signature Handling API
  slug: skribble-signature-handling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-signature-handling-api-openapi.yml
- filename: skribble-signature-observer-api-openapi.yml
  format: yaml
  label: Skribble Signature Observer API
  slug: skribble-signature-observer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-signature-observer-api-openapi.yml
- filename: skribble-signature-signer-api-openapi.yml
  format: yaml
  label: Skribble Signature Signer API
  slug: skribble-signature-signer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-signature-signer-api-openapi.yml
- filename: skribble-user-api-openapi.yml
  format: yaml
  label: Skribble User API
  slug: skribble-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-user-api-openapi.yml
- filename: skribble-validation-api-openapi.yml
  format: yaml
  label: Skribble Validation API
  slug: skribble-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/skribble/openapi/skribble-validation-api-openapi.yml
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
  - summary: Impersonation
    text: The System User shall not impersonate any person or organisation, or falsely state or otherwise misrepresent their affiliation or relationship with any such person or organisation.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: The services of PXL Vision AG may be used to verify the identity of System Users when required for the issuance of a QES, using their PXL Ident solution.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Skribble
provenance_date: '2026-11-10'
provider_name: Skribble
provider_slug: skribble
slug: skribble-eligibility
source_date: '2026-11-10'
source_filename: skribble-eligibility.yml
source_heading: Eligibility
source_page: https://www.skribble.com/en-eu/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skribble\naid: skribble\nurl: https://www.skribble.com/en-eu/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Impersonation\n  text: The System User shall not impersonate any person or organisation, or falsely state or otherwise misrepresent\n    their affiliation or relationship with any such person or organisation.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: The services of PXL Vision AG may be used to verify the identity of System Users when required for the issuance\n    of a QES,\
  \ using their PXL Ident solution.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/skribble/eligibility/skribble-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Skribble's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Signature
- Digital Signature
- Qualified Electronic Signature
- Signature Validation
- eIDAS
- Switzerland
---
