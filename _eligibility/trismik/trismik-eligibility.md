---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not access or use our Site or Platform if you are subject to sanctions imposed by the UK, EU, UN, or US, or if you are located in or operating from a country subject to comprehensive sanctions.
  entity_types:
  - text: our Individual Use Terms
    type: individual
  - text: our Business Use Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned users
    text: You must not access or use our Site or Platform if you are subject to sanctions imposed by the UK, EU, UN, or US
  - summary: Unlawful use
    text: You may use our Site and Platform only for lawful purposes.
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
name: Trismik
provenance_date: '2026-11-10'
provider_name: Trismik
provider_slug: trismik
slug: trismik-eligibility
source_date: '2026-11-10'
source_filename: trismik-eligibility.yml
source_heading: Eligibility
source_page: https://trismik.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trismik\naid: trismik\nurl: https://trismik.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not access or use our Site or Platform if you are subject to sanctions imposed by the UK, EU, UN,\n    or US, or if you are located in or operating from a country subject to comprehensive sanctions.\nentity_types:\n- type: individual\n  text: our Individual Use Terms\n- type: business\n  text: our Business Use Terms\nrestricted_uses:\n- summary: Sanctioned users\n  text: You must not access or use our Site or Platform if you are subject to sanctions imposed by the UK,\
  \ EU, UN,\n    or US\n- summary: Unlawful use\n  text: You may use our Site and Platform only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trismik/eligibility/trismik-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Trismik's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
