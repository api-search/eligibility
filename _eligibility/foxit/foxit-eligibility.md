---
api_specs:
- filename: foxit-document-generation-api-openapi.yml
  format: yaml
  label: Foxit eSign Document Generation API
  slug: foxit-document-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foxit/openapi/foxit-document-generation-api-openapi.yml
- filename: foxit-documents-api-openapi.yml
  format: yaml
  label: Foxit eSign Documents API
  slug: foxit-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foxit/openapi/foxit-documents-api-openapi.yml
- filename: foxit-foxit-esign-api-api-openapi.yml
  format: yaml
  label: Foxit eSign Foxit ESign API
  slug: foxit-foxit-esign-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foxit/openapi/foxit-foxit-esign-api-api-openapi.yml
- filename: foxit-pdf-services-api-openapi.yml
  format: yaml
  label: Foxit eSign Pdf Services API
  slug: foxit-pdf-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foxit/openapi/foxit-pdf-services-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - LY
    - KP
    - SD
    - SY
    served: []
    text: the Products or Services may not be exported or re-exported to certain countries (currently including, but not limited to, Cuba, Iran, Libya, North Korea, Sudan and Syria)
  entity_types:
  - text: If You are a business, company or an organization, you agree that upon prior request from Foxit or its authorized representative You will within thirty (30) days fully document and certify
    type: business
  minimum_age:
    text: You may only use the Products and/or Services if you are (a) over 13 years old and (b) allowed by applicable law to enter into a binding contract.
    value: '13'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: You agree to comply with all applicable foreign, federal, state and local laws and regulations governing your use of the Products and/or Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- LY
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Foxit eSign
provenance_date: '2026-11-09'
provider_name: Foxit eSign
provider_slug: foxit
slug: foxit-eligibility
source_date: '2026-11-09'
source_filename: foxit-eligibility.yml
source_heading: Eligibility
source_page: https://www.foxit.com/product/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Foxit eSign\naid: foxit\nurl: https://www.foxit.com/product/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - LY\n  - KP\n  - SD\n  - SY\n  text: the Products or Services may not be exported or re-exported to certain countries (currently including, but\n    not limited to, Cuba, Iran, Libya, North Korea, Sudan and Syria)\nentity_types:\n- type: business\n  text: If You are a business, company or an organization, you agree that upon prior request from Foxit or its authorized\n    representative You will within thirty (30) days fully document and certify\n\
  restricted_uses:\n- summary: Export and sanctions compliance\n  text: You agree to comply with all applicable foreign, federal, state and local laws and regulations governing\n    your use of the Products and/or Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may only use the Products and/or Services if you are (a) over 13 years old and (b) allowed by applicable\n    law to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/foxit/eligibility/foxit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Foxit eSign's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- Document Management
- PDF
- Cloud APIs
- Enterprise Software
- Workflow Automation
---
