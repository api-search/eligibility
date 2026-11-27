---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GH
    text: BYB Delivery is a parcel delivery service in Greater Accra, Ghana
  entity_types:
  - text: BYB Delivery built for growing businesses.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited items
    text: 'We may refuse or stop a delivery that includes: Cash, gold, jewellery or other valuables of high value, unless agreed with us in writing beforehand.'
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
name: Big Yellow Box Delivery
provenance_date: '2026-11-09'
provider_name: Big Yellow Box Delivery
provider_slug: byb-delivery
slug: byb-delivery-eligibility
source_date: '2026-11-09'
source_filename: byb-delivery-eligibility.yml
source_heading: Eligibility
source_page: https://byb.delivery/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Big Yellow Box Delivery\naid: byb-delivery\nurl: https://byb.delivery/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GH\n  excluded: []\n  text: BYB Delivery is a parcel delivery service in Greater Accra, Ghana\nentity_types:\n- type: business\n  text: BYB Delivery built for growing businesses.\nrestricted_uses:\n- summary: Prohibited items\n  text: 'We may refuse or stop a delivery that includes: Cash, gold, jewellery or other valuables of high value,\n    unless agreed with us in writing beforehand.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/byb-delivery/eligibility/byb-delivery-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Big Yellow Box Delivery's own page on 2026-11-09.
synthetic: false
tags:
- Logistics
- Delivery
- Ghana
- Couriers
- Business
---
