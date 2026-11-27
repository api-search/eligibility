---
api_specs:
- filename: yoku-app-openapi-generated.yml
  format: yaml
  label: yoku-app API
  slug: yoku-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoku-app/openapi/_ae-authored/yoku-app-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    - BE
    - BR
    - CA
    - CN
    - DK
    - FR
    - DE
    - IN
    - IT
    - MX
    - NL
    - 'NO'
    - PL
    - SG
    - ZA
    - ES
    - SE
    - CH
    - TR
    - GB
    - US
    text: Supported countries All countries
  entity_types:
  - text: These Terms apply to all users of the Service, including developers, companies, and other entities
    type: developer
  - text: These Terms apply to all users of the Service, including developers, companies, and other entities
    type: business
  minimum_age:
    text: You must be at least 16 years old (or the minimum legal age in your jurisdiction) to use the Service.
    value: '16'
  restricted_uses:
  - summary: Fraudulent or misleading use
    text: Use the Service for fraudulent or misleading purposes
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
name: yoku-app
provenance_date: '2026-11-10'
provider_name: yoku-app
provider_slug: yoku-app
slug: yoku-app-eligibility
source_date: '2026-11-10'
source_filename: yoku-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.yoku.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: yoku-app\naid: yoku-app\nurl: https://www.yoku.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  - BE\n  - BR\n  - CA\n  - CN\n  - DK\n  - FR\n  - DE\n  - IN\n  - IT\n  - MX\n  - NL\n  - 'NO'\n  - PL\n  - SG\n  - ZA\n  - ES\n  - SE\n  - CH\n  - TR\n  - GB\n  - US\n  excluded: []\n  text: Supported countries All countries\nentity_types:\n- type: developer\n  text: These Terms apply to all users of the Service, including developers, companies, and other entities\n- type: business\n  text: These Terms apply to all users of the Service, including developers, companies, and other entities\nrestricted_uses:\n\
  - summary: Fraudulent or misleading use\n  text: Use the Service for fraudulent or misleading purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old (or the minimum legal age in your jurisdiction) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/yoku-app/eligibility/yoku-app-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from yoku-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Brands
- Data
- Software-as-a-Service
---
