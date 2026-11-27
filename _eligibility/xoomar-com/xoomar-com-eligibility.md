---
api_specs:
- filename: xoomar-com-companies-api-openapi.yml
  format: yaml
  label: XOOMAR Companies API
  slug: xoomar-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xoomar-com/openapi/xoomar-com-companies-api-openapi.yml
- filename: xoomar-com-crypto-api-openapi.yml
  format: yaml
  label: XOOMAR Crypto API
  slug: xoomar-com-crypto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xoomar-com/openapi/xoomar-com-crypto-api-openapi.yml
- filename: xoomar-com-macro-api-openapi.yml
  format: yaml
  label: XOOMAR Macro API
  slug: xoomar-com-macro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xoomar-com/openapi/xoomar-com-macro-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 or older, or the age of majority where you live, to open an account.
    type: individual
  - text: If you use the Service for an organisation, you accept them for that organisation and confirm you may do so.
    type: business
  minimum_age:
    text: You must be 18 or older, or the age of majority where you live, to open an account.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: No use that breaks a law or a regulation, including securities, sanctions, export and data-protection law.
  - summary: Sanctions
    text: You confirm that you are not on a sanctions list and will not use the Service where the law prohibits it.
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
name: XOOMAR
provenance_date: '2026-11-10'
provider_name: XOOMAR
provider_slug: xoomar-com
slug: xoomar-com-eligibility
source_date: '2026-11-10'
source_filename: xoomar-com-eligibility.yml
source_heading: Eligibility
source_page: https://xoomar.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: XOOMAR\naid: xoomar-com\nurl: https://xoomar.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 or older, or the age of majority where you live, to open an account.\n- type: business\n  text: If you use the Service for an organisation, you accept them for that organisation and confirm you may do\n    so.\nrestricted_uses:\n- summary: Unlawful use\n  text: No use that breaks a law or a regulation, including securities, sanctions, export and data-protection law.\n- summary: Sanctions\n  text: You confirm that you\
  \ are not on a sanctions list and will not use the Service where the law prohibits it.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older, or the age of majority where you live, to open an account.\n"
source_yaml_url: https://artifacts.apis.io/xoomar-com/eligibility/xoomar-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from XOOMAR's own page on 2026-11-10.
synthetic: false
tags:
- Capital Markets
- Data
- Financial Services
- Software
---
