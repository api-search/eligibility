---
api_specs:
- filename: attestwire-com-billing-api-openapi.yml
  format: yaml
  label: Attestwire Billing API
  slug: attestwire-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-billing-api-openapi.yml
- filename: attestwire-com-diagnose-api-openapi.yml
  format: yaml
  label: Attestwire Diagnose API
  slug: attestwire-com-diagnose-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-diagnose-api-openapi.yml
- filename: attestwire-com-invoices-api-openapi.yml
  format: yaml
  label: Attestwire Invoices API
  slug: attestwire-com-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-invoices-api-openapi.yml
- filename: attestwire-com-keys-api-openapi.yml
  format: yaml
  label: Attestwire Keys API
  slug: attestwire-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-keys-api-openapi.yml
- filename: attestwire-com-meta-api-openapi.yml
  format: yaml
  label: Attestwire Meta API
  slug: attestwire-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-meta-api-openapi.yml
- filename: attestwire-com-peppol-api-openapi.yml
  format: yaml
  label: Attestwire Peppol API
  slug: attestwire-com-peppol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-peppol-api-openapi.yml
- filename: attestwire-com-recipient-api-openapi.yml
  format: yaml
  label: Attestwire Recipient API
  slug: attestwire-com-recipient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-recipient-api-openapi.yml
- filename: attestwire-com-records-api-openapi.yml
  format: yaml
  label: Attestwire Records API
  slug: attestwire-com-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-records-api-openapi.yml
- filename: attestwire-com-vat-api-openapi.yml
  format: yaml
  label: Attestwire Vat API
  slug: attestwire-com-vat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestwire-com/openapi/attestwire-com-vat-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These terms are between you (the person or company using the API)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Data without rights
    text: send data you have no right to send, or use the API to break a law that applies to you
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: a free signup address is never verified
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Attestwire
provenance_date: '2026-11-09'
provider_name: Attestwire
provider_slug: attestwire-com
slug: attestwire-com-eligibility
source_date: '2026-11-09'
source_filename: attestwire-com-eligibility.yml
source_heading: Eligibility
source_page: https://attestwire.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Attestwire\naid: attestwire-com\nurl: https://attestwire.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These terms are between you (the person or company using the API)\nrestricted_uses:\n- summary: Data without rights\n  text: send data you have no right to send, or use the API to break a law that applies to you\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: a free signup address is never verified\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/attestwire-com/eligibility/attestwire-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Attestwire's own page on 2026-11-09.
synthetic: false
tags:
- Attestwire
- e-invoice
- Validation
- XRechnung
- Peppol
- MCP
---
