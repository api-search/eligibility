---
api_specs:
- filename: lili-lili-api-openapi.yml
  format: yaml
  label: Lili API
  slug: lili-lili-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lili/openapi/lili-lili-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your use of the Lili Services and Lili Account are for commercial or business purposes only
    type: business
  - text: you are 18 years of age (or 19 for Alabama and Nebraska residents) or older
    type: individual
  minimum_age:
    text: you are 18 years of age (or 19 for Alabama and Nebraska residents) or older
    value: '18'
  restricted_uses:
  - summary: No consumer/personal use
    text: you will not use the Account for any consumer (i.e., personal, family, or household) purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You hereby authorize us, directly or through third parties, to make any inquiries we consider necessary to validate your identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lili
provenance_date: '2026-11-09'
provider_name: Lili
provider_slug: lili
slug: lili-eligibility
source_date: '2026-11-09'
source_filename: lili-eligibility.yml
source_heading: Eligibility
source_page: https://lili.co/legal-documents/lili-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lili\naid: lili\nurl: https://lili.co/legal-documents/lili-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Your use of the Lili Services and Lili Account are for commercial or business purposes only\n- type: individual\n  text: you are 18 years of age (or 19 for Alabama and Nebraska residents) or older\nrestricted_uses:\n- summary: No consumer/personal use\n  text: you will not use the Account for any consumer (i.e., personal, family, or household) purpose.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n\
  \  text: You hereby authorize us, directly or through third parties, to make any inquiries we consider necessary\n    to validate your identity\nminimum_age:\n  value: '18'\n  text: you are 18 years of age (or 19 for Alabama and Nebraska residents) or older\n"
source_yaml_url: https://artifacts.apis.io/lili/eligibility/lili-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Lili's own page on 2026-11-09.
synthetic: false
tags:
- Banking
- Business Banking
- Financial Services
- Fintech
- Embedded Finance
- Onboarding
- KYC
- Webhook
- MCP
- Agent-Native
- Invoicing
- Bill Pay
- Accounting
- Small Business
---
