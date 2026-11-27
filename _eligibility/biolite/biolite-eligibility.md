---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: All sales and payments will be in US Dollars for the BioLite US Shop, CAD for the Canada Shop, and EUR for the EU Shop.
  entity_types:
  - text: BioLite sells Products on the Site to end-user customers only for their own personal, non-commercial use.
    type: individual
  - text: You may not purchase any Products for further distribution or resale or for any other commercial or business purpose
    type: business
  minimum_age:
    text: By using the Site, you represent, acknowledge and agree that you are at least 18 years of age, or if you are under 18 years of age but are at least 13 years old, that you are using the Site with the consent of your parent or legal guardian
    value: '13'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: BioLite sells Products on the Site to end-user customers only for their own personal, non-commercial use.
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
name: Biolite
provenance_date: '2026-11-09'
provider_name: Biolite
provider_slug: biolite
slug: biolite-eligibility
source_date: '2026-11-09'
source_filename: biolite-eligibility.yml
source_heading: Eligibility
source_page: https://www.bioliteenergy.com/pages/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Biolite\naid: biolite\nurl: https://www.bioliteenergy.com/pages/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: All sales and payments will be in US Dollars for the BioLite US Shop, CAD for the Canada Shop, and EUR for\n    the EU Shop.\nentity_types:\n- type: individual\n  text: BioLite sells Products on the Site to end-user customers only for their own personal, non-commercial use.\n- type: business\n  text: You may not purchase any Products for further distribution or resale or for any other commercial or business\n    purpose\nrestricted_uses:\n\
  - summary: Personal non-commercial use only\n  text: BioLite sells Products on the Site to end-user customers only for their own personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: By using the Site, you represent, acknowledge and agree that you are at least 18 years of age, or if you\n    are under 18 years of age but are at least 13 years old, that you are using the Site with the consent of your\n    parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/biolite/eligibility/biolite-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Biolite's own page on 2026-11-09.
synthetic: false
tags:
- Lighting
- Portable Power
- Cooking
- Outdoor Gear
- Home Backup
---
