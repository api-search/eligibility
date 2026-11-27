---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is controlled and primarily operated by Nix in the United States.
  entity_types:
  - text: User represents and warrants that User is at least 18 years of age and of the legal age to form a binding contract in their jurisdiction.
    type: individual
  minimum_age:
    text: User represents and warrants that User is at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: User agrees not to upload, post, email, or otherwise transmit through the Site or Services any Content or any other materials whatsoever that are or could appear to be
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
name: Nix
provenance_date: '2026-11-10'
provider_name: Nix
provider_slug: nix
slug: nix-eligibility
source_date: '2026-11-10'
source_filename: nix-eligibility.yml
source_heading: Eligibility
source_page: https://nixbiosensors.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nix\naid: nix\nurl: https://nixbiosensors.com/pages/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is controlled and primarily operated by Nix in the United States.\nentity_types:\n- type: individual\n  text: User represents and warrants that User is at least 18 years of age and of the legal age to form a binding\n    contract in their jurisdiction.\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: User agrees not to upload, post, email, or otherwise transmit through the Site or Services any Content or\n    any other materials whatsoever\
  \ that are or could appear to be\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: User represents and warrants that User is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/nix/eligibility/nix-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Nix's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biosensors
- Wearables
- Hydration
- Health
- Sports
- IoT
---
