---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country; and (ii) you are not listed on any U.S. Government list of prohibited or restricted parties.
  minimum_age:
    text: The Site are available to registered and unregistered users who are 13 years old and older
    value: '13'
  restricted_uses:
  - summary: No fraudulent or unlawful use
    text: Engaging in conduct that would constitute a criminal offense or give rise to civil liability or otherwise violate any law or regulation
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
name: Bokksu
provenance_date: '2026-11-09'
provider_name: Bokksu
provider_slug: bokksu
slug: bokksu-eligibility
source_date: '2026-11-09'
source_filename: bokksu-eligibility.yml
source_heading: Eligibility
source_page: https://bokksu.com/pages/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bokksu\naid: bokksu\nurl: https://bokksu.com/pages/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country; and (ii) you\n    are not listed on any U.S. Government list of prohibited or restricted parties.\nentity_types: []\nrestricted_uses:\n- summary: No fraudulent or unlawful use\n  text: Engaging in conduct that would constitute a criminal offense or give rise to civil\
  \ liability or otherwise\n    violate any law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site are available to registered and unregistered users who are 13 years old and older\n"
source_yaml_url: https://artifacts.apis.io/bokksu/eligibility/bokksu-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bokksu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Subscription
- Snacks
- Japan
- E-Commerce
---
