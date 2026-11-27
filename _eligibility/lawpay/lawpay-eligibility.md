---
api_specs:
- filename: lawpay-openapi-generated.yml
  format: yaml
  label: LawPay API
  slug: lawpay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lawpay/openapi/_ae-authored/lawpay-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Platform is intended to be used by legal, accounting, other client-based professionals located in the United States and Canada.
  entity_types:
  - text: we provide a range of Services to legal, accounting, and other client-based professionals located in the United States and Canada.
    type: business
  minimum_age:
    text: You are at least 18 years of age and are capable of entering into a binding contract
    value: '18'
  restricted_uses:
  - summary: Minors
    text: allow minors to use the Platform, in either case, without written consent from their parent or guardian or unless otherwise permitted by applicable law
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
name: LawPay
provenance_date: '2026-11-09'
provider_name: LawPay
provider_slug: lawpay
slug: lawpay-eligibility
source_date: '2026-11-09'
source_filename: lawpay-eligibility.yml
source_heading: Eligibility
source_page: https://www.8am.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LawPay\naid: lawpay\nurl: https://www.8am.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Platform is intended to be used by legal, accounting, other client-based professionals located in the United\n    States and Canada.\nentity_types:\n- type: business\n  text: we provide a range of Services to legal, accounting, and other client-based professionals located in the\n    United States and Canada.\nrestricted_uses:\n- summary: Minors\n  text: allow minors to use the Platform, in either case, without written consent from their\
  \ parent or guardian\n    or unless otherwise permitted by applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age and are capable of entering into a binding contract\n"
source_yaml_url: https://artifacts.apis.io/lawpay/eligibility/lawpay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LawPay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Legal Tech
- Fintech
- Software-as-a-Service
---
