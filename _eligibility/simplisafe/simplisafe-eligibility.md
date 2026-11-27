---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Purchases from SimpliSafe, an authorized sales representative, or any authorized retailer are available only in the United States.
  entity_types:
  - text: Purchases made through the SimpliSafe website or from any authorized retailers are for end user customers only.
    type: individual
  - text: Where applicable and not otherwise prohibited by these Terms of Sale, you may purchase a System on behalf of a business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Cameras not in privacy-expectation areas
    text: you shall not use or permit the use of a Camera installed with a view where any person may have a reasonable expectation of privacy, including bedrooms, restrooms, dressing or changing areas, locker rooms or similar areas
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
name: SimpliSafe
provenance_date: '2026-11-10'
provider_name: SimpliSafe
provider_slug: simplisafe
slug: simplisafe-eligibility
source_date: '2026-11-10'
source_filename: simplisafe-eligibility.yml
source_heading: Eligibility
source_page: https://simplisafe.com/legal/terms-sale
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SimpliSafe\naid: simplisafe\nurl: https://simplisafe.com/legal/terms-sale\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Purchases from SimpliSafe, an authorized sales representative, or any authorized retailer are available\n    only in the United States.\nentity_types:\n- type: individual\n  text: Purchases made through the SimpliSafe website or from any authorized retailers are for end user customers\n    only.\n- type: business\n  text: Where applicable and not otherwise prohibited by these Terms of Sale, you may purchase a System on behalf\n    of a business\nrestricted_uses:\n\
  - summary: Cameras not in privacy-expectation areas\n  text: you shall not use or permit the use of a Camera installed with a view where any person may have a reasonable\n    expectation of privacy, including bedrooms, restrooms, dressing or changing areas, locker rooms or similar areas\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/simplisafe/eligibility/simplisafe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from SimpliSafe's own page on 2026-11-10.
synthetic: false
tags:
- Home Security
- Wireless
- Alarms
- Security Systems
---
