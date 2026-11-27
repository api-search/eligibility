---
api_specs:
- filename: nitro-software-authentication-api-openapi.yml
  format: yaml
  label: Nitro Software Authentication API
  slug: nitro-software-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nitro-software/openapi/nitro-software-authentication-api-openapi.yml
- filename: nitro-software-platform-api-openapi.yml
  format: yaml
  label: Nitro Software Platform API
  slug: nitro-software-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nitro-software/openapi/nitro-software-platform-api-openapi.yml
- filename: nitro-software-sign-api-openapi.yml
  format: yaml
  label: Nitro Software Sign API
  slug: nitro-software-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nitro-software/openapi/nitro-software-sign-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the Customer is a business signing up with its legal entity, the relevant Data Processing Addendum applies
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO ENTER INTO A BINDING AGREEMENT
    value: legal age
  restricted_uses:
  - summary: No benchmark publication during trial
    text: Customer shall not publish any results of benchmark tests run on the Services or disclose its features, errors or bugs to a third party without Nitro’s prior written consent.
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
name: Nitro Software
provenance_date: '2026-11-10'
provider_name: Nitro Software
provider_slug: nitro-software
slug: nitro-software-eligibility
source_date: '2026-11-10'
source_filename: nitro-software-eligibility.yml
source_heading: Eligibility
source_page: https://www.gonitro.com/legal/pdf-sign/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nitro Software\naid: nitro-software\nurl: https://www.gonitro.com/legal/pdf-sign/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the Customer is a business signing up with its legal entity, the relevant Data Processing Addendum applies\nrestricted_uses:\n- summary: No benchmark publication during trial\n  text: Customer shall not publish any results of benchmark tests run on the Services or disclose its features,\n    errors or bugs to a third party without Nitro’s prior written consent.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: YOU ARE OF LEGAL AGE TO ENTER INTO A BINDING AGREEMENT\n"
source_yaml_url: https://artifacts.apis.io/nitro-software/eligibility/nitro-software-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Nitro Software's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Documents
- E-Signature
- Document Management
- Document Intelligence
- OCR
- Data Extraction
- Productivity
---
