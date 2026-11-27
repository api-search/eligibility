---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: As a user of the App, you warrant that you are not located in a country that is subject to a U.S. Government embargo and not listed on any U.S. Government list of prohibited or restricted parties.
  entity_types:
  - text: The use of our Website and Services is limited to persons who are considered of legal age and that can lawfully enter into and form contracts under applicable law.
    type: individual
  minimum_age:
    text: Those persons under the age of 18 are not eligible to use the Applications and that you are older than 18.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: The Website may be used only for lawful purposes and in a lawful manner.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To register on the Website, as a user, you must provide your legal name, address, phone number and e-mail address
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Thematic
provenance_date: '2026-11-10'
provider_name: Thematic
provider_slug: thematic
slug: thematic-eligibility
source_date: '2026-11-10'
source_filename: thematic-eligibility.yml
source_heading: Eligibility
source_page: https://hellothematic.com/terms-of-use-privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thematic\naid: thematic\nurl: https://hellothematic.com/terms-of-use-privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: As a user of the App, you warrant that you are not located in a country that is subject to a U.S. Government\n    embargo and not listed on any U.S. Government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: The use of our Website and Services is limited to persons who are considered of legal age and that can lawfully\n    enter into and form contracts under applicable law.\nrestricted_uses:\n- summary: Lawful use\
  \ only\n  text: The Website may be used only for lawful purposes and in a lawful manner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To register on the Website, as a user, you must provide your legal name, address, phone number and e-mail\n    address\nminimum_age:\n  value: '18'\n  text: Those persons under the age of 18 are not eligible to use the Applications and that you are older than 18.\n"
source_yaml_url: https://artifacts.apis.io/thematic/eligibility/thematic-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Thematic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Music
- Music Licensing
- Content Creators
- Creator Economy
- Copyright
- Royalty-Free Music
- Media
- Audio
---
