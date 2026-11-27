---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Vilkårene er utarbeidet i samsvar med forbrukerkjøpsloven, angrerettloven og øvrig relevant norsk lovgivning
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Right-of-withdrawal exceptions
    text: 'Unntak fra angreretten gjelder blant annet for: Undertøy, badetøy og øredobber der forsegling er brutt'
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
name: Villoid
provenance_date: '2026-11-10'
provider_name: Villoid
provider_slug: villoid
slug: villoid-eligibility
source_date: '2026-11-10'
source_filename: villoid-eligibility.yml
source_heading: Eligibility
source_page: https://villoid.no/pages/kjopsvilkar
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Villoid\naid: villoid\nurl: https://villoid.no/pages/kjopsvilkar\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Vilkårene er utarbeidet i samsvar med forbrukerkjøpsloven, angrerettloven og øvrig relevant norsk lovgivning\nrestricted_uses:\n- summary: Right-of-withdrawal exceptions\n  text: 'Unntak fra angreretten gjelder blant annet for: Undertøy, badetøy og øredobber der forsegling er brutt'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/villoid/eligibility/villoid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Villoid's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fashion
- E-Commerce
- Retail
- Shopping
- Apparel
- Norway
- Shopify
---
