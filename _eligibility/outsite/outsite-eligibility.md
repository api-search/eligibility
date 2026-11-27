---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Membership Subscription is only available to those individuals who are 21 years of age or older.
    type: individual
  minimum_age:
    text: The Site and our rentals will only be rented to those persons who are 21 years of age or older.
    value: '21'
  restricted_uses:
  - summary: No pets
    text: No pets, including dogs, cats, birds, fish or other domestic pet or animal of any kind may be kept on or about the property without Outsite’s written consent.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Outsite Inc reserves the right to screen the Member by asking for the Member’s full name, date of birth, profile links and photo identification in order to determine the Member’s eligibility for the Membership Subscription.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Outsite
provenance_date: '2026-11-10'
provider_name: Outsite
provider_slug: outsite
slug: outsite-eligibility
source_date: '2026-11-10'
source_filename: outsite-eligibility.yml
source_heading: Eligibility
source_page: https://www.outsite.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Outsite\naid: outsite\nurl: https://www.outsite.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Membership Subscription is only available to those individuals who are 21 years of age or older.\nrestricted_uses:\n- summary: No pets\n  text: No pets, including dogs, cats, birds, fish or other domestic pet or animal of any kind may be kept on or\n    about the property without Outsite’s written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Outsite Inc reserves the\
  \ right to screen the Member by asking for the Member’s full name, date of birth,\n    profile links and photo identification in order to determine the Member’s eligibility for the Membership Subscription.\nminimum_age:\n  value: '21'\n  text: The Site and our rentals will only be rented to those persons who are 21 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/outsite/eligibility/outsite-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Outsite's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Co-Living
- Co-Working
- Remote Work
- Digital Nomads
- Travel
- Hospitality
- Membership
- Community
---
