---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Booktrack makes no representations that the Booktrack Website or Platform is appropriate or available for use in your location.
  entity_types:
  - text: You affirm that you are either more than the age of majority in your jurisdiction of residence, or an emancipated minor, or possess legal parental or guardian consent
    type: individual
  minimum_age:
    text: You will not create an account if you are under 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Website not intended for children under 13
    text: the Booktrack Website is not intended for children younger than 13
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to confirm your identity before we delete your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Booktrack
provenance_date: '2026-11-09'
provider_name: Booktrack
provider_slug: booktrack
slug: booktrack-eligibility
source_date: '2026-11-09'
source_filename: booktrack-eligibility.yml
source_heading: Eligibility
source_page: https://www.booktrack.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Booktrack\naid: booktrack\nurl: https://www.booktrack.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Booktrack makes no representations that the Booktrack Website or Platform is appropriate or available for\n    use in your location.\nentity_types:\n- type: individual\n  text: You affirm that you are either more than the age of majority in your jurisdiction of residence, or an emancipated\n    minor, or possess legal parental or guardian consent\nrestricted_uses:\n- summary: Website not intended for children under 13\n  text: the Booktrack Website is not intended for children\
  \ younger than 13\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to confirm your identity before we delete your account.\nminimum_age:\n  value: '13'\n  text: You will not create an account if you are under 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/booktrack/eligibility/booktrack-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Booktrack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Audiobooks
- Production
- Technology
- Publishing
---
