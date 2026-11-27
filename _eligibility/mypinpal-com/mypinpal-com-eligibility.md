---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use Pinpal if you are located in a country under a United States government embargo or designated by the United States as a "terrorist supporting" country, or if you are on any United States government list of prohibited or restricted parties.
  entity_types:
  - text: You must be at least 13 years old.
    type: individual
  minimum_age:
    text: You must be at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful storage or sharing
    text: You agree not to use Pinpal to store or share anything unlawful, infringing, or harmful
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with Apple or Google.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: mypinpal-com
provenance_date: '2026-11-10'
provider_name: mypinpal-com
provider_slug: mypinpal-com
slug: mypinpal-com-eligibility
source_date: '2026-11-10'
source_filename: mypinpal-com-eligibility.yml
source_heading: Eligibility
source_page: https://mypinpal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mypinpal-com\naid: mypinpal-com\nurl: https://mypinpal.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use Pinpal if you are located in a country under a United States government embargo or designated\n    by the United States as a \"terrorist supporting\" country, or if you are on any United States government list\n    of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old.\nrestricted_uses:\n- summary: Unlawful or harmful storage or sharing\n  text: You agree not to use Pinpal to store or share anything\
  \ unlawful, infringing, or harmful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with Apple or Google.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/mypinpal-com/eligibility/mypinpal-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from mypinpal-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Productivity
- Notes
- Project
- Sweden
---
