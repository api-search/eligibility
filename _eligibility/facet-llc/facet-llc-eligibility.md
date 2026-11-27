---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Customer is not located in, and is not a national or resident of, any country or region subject to comprehensive sanctions administered by the U.S. Treasury Department's Office of Foreign Assets Control (OFAC) , as of the Effective Date including Cuba, Iran, North Korea, Syria
  entity_types:
  - text: the organization or individual accepting these terms
    type: individual
  - text: If Customer is accepting on behalf of an organization, Customer represents that Customer has the authority to bind that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned or restricted-party use
    text: Customer is not listed on OFAC's Specially Designated Nationals and Blocked Persons List
  - summary: Weapons development
    text: Customer will not use the Services in connection with the development, production, or use of nuclear, chemical, or biological weapons or missiles capable of delivering such weapons.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Facet
provenance_date: '2026-11-09'
provider_name: Facet
provider_slug: facet-llc
slug: facet-llc-eligibility
source_date: '2026-11-09'
source_filename: facet-llc-eligibility.yml
source_heading: Eligibility
source_page: https://facet.llc/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Facet\naid: facet-llc\nurl: https://facet.llc/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Customer is not located in, and is not a national or resident of, any country or region subject to comprehensive\n    sanctions administered by the U.S. Treasury Department's Office of Foreign Assets Control (OFAC) , as of the\n    Effective Date including Cuba, Iran, North Korea, Syria\nentity_types:\n- type: individual\n  text: the organization or individual accepting these terms\n- type: business\n  text: If Customer is accepting on behalf of an\
  \ organization, Customer represents that Customer has the authority\n    to bind that organization\nrestricted_uses:\n- summary: Sanctioned or restricted-party use\n  text: Customer is not listed on OFAC's Specially Designated Nationals and Blocked Persons List\n- summary: Weapons development\n  text: Customer will not use the Services in connection with the development, production, or use of nuclear, chemical,\n    or biological weapons or missiles capable of delivering such weapons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/facet-llc/eligibility/facet-llc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Facet's own page on 2026-11-09.
synthetic: false
tags:
- Commerce
- Payments
- Artificial Intelligence
- Agentic Commerce
- Marketplace
---
