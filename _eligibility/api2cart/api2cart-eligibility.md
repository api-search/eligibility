---
api_specs:
- filename: api2cart-account-failed-webhooks-json-api-openapi.yml
  format: yaml
  label: Lexy Mayko Account.failed Webhooks.json API
  slug: api2cart-account-failed-webhooks-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/api2cart/openapi/api2cart-account-failed-webhooks-json-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    - CU
    - IR
    - LY
    - KP
    - SD
    - SY
    - MM
    served: []
    text: is not registered in the country or territory that is the subject of sanctions or the government of which is the subject of sanctions (including, but not limited to, the Russian Federation, the Republic of Belarus, the DNR, LNR, Crimea, Myanmar (Burma), Cuba, Iran, Libya, North Korea, Sudan, Syria)
  entity_types:
  - text: If you are entering into these Terms of Service on behalf of an entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: You must be legally adult (at the age of majority) or older to use the Site or the Service.
    value: age of majority
  restricted_uses:
  - summary: Unlawful or infringing data
    text: 'Receiving, processing, storing or disseminating through the Service any information data that: violates applicable law'
  - summary: Sanctioned parties
    text: If API2Cart finds that you are under any of the Sanctions, then API2Cart has the right to immediately unilaterally terminate any contractual relations with you
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your legal full name, a valid email address, and any other information requested in order to complete the signup process
excluded_countries:
- RU
- BY
- CU
- IR
- LY
- KP
- SD
- SY
- MM
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lexy Mayko
provenance_date: '2026-11-09'
provider_name: Lexy Mayko
provider_slug: api2cart
slug: api2cart-eligibility
source_date: '2026-11-09'
source_filename: api2cart-eligibility.yml
source_heading: Eligibility
source_page: https://api2cart.com/terms-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lexy Mayko\naid: api2cart\nurl: https://api2cart.com/terms-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  - CU\n  - IR\n  - LY\n  - KP\n  - SD\n  - SY\n  - MM\n  text: is not registered in the country or territory that is the subject of sanctions or the government of which\n    is the subject of sanctions (including, but not limited to, the Russian Federation, the Republic of Belarus,\n    the DNR, LNR, Crimea, Myanmar (Burma), Cuba, Iran, Libya, North Korea, Sudan, Syria)\nentity_types:\n- type: business\n  text: If you are entering into these Terms of Service on\
  \ behalf of an entity, you represent that you have the\n    authority to bind such entity\nrestricted_uses:\n- summary: Unlawful or infringing data\n  text: 'Receiving, processing, storing or disseminating through the Service any information data that: violates\n    applicable law'\n- summary: Sanctioned parties\n  text: If API2Cart finds that you are under any of the Sanctions, then API2Cart has the right to immediately unilaterally\n    terminate any contractual relations with you\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your legal full name, a valid email address, and any other information requested in order\n    to complete the signup process\nminimum_age:\n  value: age of majority\n  text: You must be legally adult (at the age of majority) or older to use the Site or the Service.\n"
source_yaml_url: https://artifacts.apis.io/api2cart/eligibility/api2cart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Lexy Mayko's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Integration
- Software-as-a-Service
- Marketplace
---
