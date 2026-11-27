---
api_specs:
- filename: columbia-sportswear-externalimage-api-openapi.yml
  format: yaml
  label: Columbia Sportswear External Image API
  slug: columbia-sportswear-externalimage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/columbia-sportswear/openapi/columbia-sportswear-externalimage-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Sites are intended for use by adults in the U.S.
  entity_types:
  - text: The Sites are intended for use by adults in the U.S.
    type: individual
  - text: If you are using the Sites on behalf of any entity, you represent and warrant that you are authorized to accept these Site Terms on such entity's behalf
    type: business
  minimum_age:
    text: The Sites are intended for use by adults in the U.S. You agree to monitor your account and restrict use by minors.
    value: adult
  restricted_uses:
  - summary: Commercial purpose use of the Sites or account
    text: Use the Sites or your account for a commercial purpose;
  - summary: Sanctioned persons
    text: You may not use the Sites if you are the subject of U.S. sanctions
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
name: Columbia Sportswear
provenance_date: '2026-11-09'
provider_name: Columbia Sportswear
provider_slug: columbia-sportswear
slug: columbia-sportswear-eligibility
source_date: '2026-11-09'
source_filename: columbia-sportswear-eligibility.yml
source_heading: Eligibility
source_page: https://www.columbia.com/t/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Columbia Sportswear\naid: columbia-sportswear\nurl: https://www.columbia.com/t/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Sites are intended for use by adults in the U.S.\nentity_types:\n- type: individual\n  text: The Sites are intended for use by adults in the U.S.\n- type: business\n  text: If you are using the Sites on behalf of any entity, you represent and warrant that you are authorized to\n    accept these Site Terms on such entity's behalf\nrestricted_uses:\n- summary: Commercial purpose use of the Sites or account\n  text: Use the Sites\
  \ or your account for a commercial purpose;\n- summary: Sanctioned persons\n  text: You may not use the Sites if you are the subject of U.S. sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adult\n  text: The Sites are intended for use by adults in the U.S. You agree to monitor your account and restrict use\n    by minors.\n"
source_yaml_url: https://artifacts.apis.io/columbia-sportswear/eligibility/columbia-sportswear-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Columbia Sportswear's own page on 2026-11-09.
synthetic: false
tags:
- Apparel
- B2B
- Consumer Management
- Content Management
- Digital Asset Management
- Footwear
- Fortune 1000
- Outdoor
- Partner API
- Product Imagery
- Retail
- Fashion
---
