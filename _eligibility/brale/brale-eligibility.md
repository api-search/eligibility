---
api_specs:
- filename: brale-accounts-api-openapi.yml
  format: yaml
  label: Brale Accounts API
  slug: brale-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brale/openapi/brale-accounts-api-openapi.yml
- filename: brale-addresses-api-openapi.yml
  format: yaml
  label: Brale Addresses API
  slug: brale-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brale/openapi/brale-addresses-api-openapi.yml
- filename: brale-automations-api-openapi.yml
  format: yaml
  label: Brale Automations API
  slug: brale-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brale/openapi/brale-automations-api-openapi.yml
- filename: brale-financial-institutions-api-openapi.yml
  format: yaml
  label: Brale Financial Institutions API
  slug: brale-financial-institutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brale/openapi/brale-financial-institutions-api-openapi.yml
- filename: brale-orders-api-openapi.yml
  format: yaml
  label: Brale Orders API
  slug: brale-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brale/openapi/brale-orders-api-openapi.yml
- filename: brale-plaid-api-openapi.yml
  format: yaml
  label: Brale Plaid API
  slug: brale-plaid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brale/openapi/brale-plaid-api-openapi.yml
- filename: brale-transfers-api-openapi.yml
  format: yaml
  label: Brale Transfers API
  slug: brale-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brale/openapi/brale-transfers-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual user, you agree not to use the Services on behalf of or for the benefit of any third party except as permitted under a Services Agreement.
    type: individual
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization's or entity's behalf
    type: business
  minimum_age:
    text: You must be at least 13 years of age to sign up for an account
    value: '13'
  restricted_uses:
  - summary: Compliance with applicable law
    text: You will only use the Services in a manner that complies with all laws that apply to you.
  - summary: Prohibited uses of the Services
    text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable
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
name: Brale
provenance_date: '2026-11-09'
provider_name: Brale
provider_slug: brale
slug: brale-eligibility
source_date: '2026-11-09'
source_filename: brale-eligibility.yml
source_heading: Eligibility
source_page: https://brale.xyz/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brale\naid: brale\nurl: https://brale.xyz/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual user, you agree not to use the Services on behalf of or for the benefit of any\n    third party except as permitted under a Services Agreement.\n- type: business\n  text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization's or entity's behalf\nrestricted_uses:\n- summary: Compliance with\
  \ applicable law\n  text: You will only use the Services in a manner that complies with all laws that apply to you.\n- summary: Prohibited uses of the Services\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to sign up for an account\n"
source_yaml_url: https://artifacts.apis.io/brale/eligibility/brale-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Brale's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Stablecoins
- Stablecoin Issuance
- Payments
- Blockchain
- Cryptocurrency
- Fintech
- Financial Services
- Custody
- Tokenization
- On-Ramp
- Off-Ramp
- A2A
---
