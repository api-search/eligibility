---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using this site, you confirm that you are at least the age of majority in your state or country of residence, or that you are using the site under the supervision of a parent or legal guardian.
    type: individual
  minimum_age:
    text: you confirm that you are at least the age of majority in your state or country of residence, or that you are using the site under the supervision of a parent or legal guardian.
    value: null
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
name: Osmo
provenance_date: '2026-11-10'
provider_name: Osmo
provider_slug: osmo
slug: osmo-eligibility
source_date: '2026-11-10'
source_filename: osmo-eligibility.yml
source_heading: Eligibility
source_page: https://www.playosmo.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Osmo\naid: osmo\nurl: https://www.playosmo.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using this site, you confirm that you are at least the age of majority in your state or country of residence,\n    or that you are using the site under the supervision of a parent or legal guardian.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you confirm that you are at least the age of majority in your state or country\
  \ of residence, or that you\n    are using the site under the supervision of a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/osmo/eligibility/osmo-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Osmo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Education
- EdTech
- Children
- Games
- Hardware
- Learning
---
