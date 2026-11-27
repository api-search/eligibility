---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: you are a resident of the U.S., or its territories, or Canada
  minimum_age:
    text: UNDER NO CIRCUMSTANCES MAY YOU ACCESS OR USE THIS SITE OR ANY IPSY SERVICE IF YOU ARE UNDER THIRTEEN (13) YEARS OLD.
    value: '13'
  restricted_uses:
  - summary: Resale of purchased products
    text: Products received through your IPSY Box subscription are for individual use only, and we do not authorize the purchase of such merchandise for resale purposes.
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
name: Ipsy
provenance_date: '2026-11-09'
provider_name: Ipsy
provider_slug: ipsy
slug: ipsy-eligibility
source_date: '2026-11-09'
source_filename: ipsy-eligibility.yml
source_heading: Eligibility
source_page: https://www.ipsy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ipsy\naid: ipsy\nurl: https://www.ipsy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: you are a resident of the U.S., or its territories, or Canada\nentity_types: []\nrestricted_uses:\n- summary: Resale of purchased products\n  text: Products received through your IPSY Box subscription are for individual use only, and we do not authorize\n    the purchase of such merchandise for resale purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: UNDER NO CIRCUMSTANCES MAY YOU ACCESS OR USE\
  \ THIS SITE OR ANY IPSY SERVICE IF YOU ARE UNDER THIRTEEN (13)\n    YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/ipsy/eligibility/ipsy-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ipsy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Beauty
- Cosmetics
- Subscription
- E-Commerce
- Direct to Consumer
- Personalization
- Membership
---
