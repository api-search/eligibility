---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Advertising or selling goods and services
    text: Use the Site to advertise or offer to sell goods and services.
  - summary: Buying agents making purchases
    text: Use a buying agent or purchasing agent to make purchases on the Site.
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
name: MiRus
provenance_date: '2026-11-10'
provider_name: MiRus
provider_slug: mirus
slug: mirus-eligibility
source_date: '2026-11-10'
source_filename: mirus-eligibility.yml
source_heading: Eligibility
source_page: https://www.mirusmed.com/wp-content/uploads/2021/10/MiRus-Terms-of-Use-Policy.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MiRus\naid: mirus\nurl: https://www.mirusmed.com/wp-content/uploads/2021/10/MiRus-Terms-of-Use-Policy.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Advertising or selling goods and services\n  text: Use the Site to advertise or offer to sell goods and services.\n\
  - summary: Buying agents making purchases\n  text: Use a buying agent or purchasing agent to make purchases on the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is intended for users who are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/mirus/eligibility/mirus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from MiRus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Medical Devices
- Healthcare
- Life Sciences
- Spine
- Orthopaedics
- Structural Heart
- Remote Patient Monitoring
- Medical Implants
- Surgical Planning
---
