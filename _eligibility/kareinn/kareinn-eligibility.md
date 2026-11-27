---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Site is intended for users who are at least 18 years old.
    type: individual
  minimum_age:
    text: Persons under the age of 18 are not permitted to use or register for the Site.
    value: '18'
  restricted_uses:
  - summary: Commercial endeavors restricted
    text: The Site may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by us.
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
name: KareInn
provenance_date: '2026-11-09'
provider_name: KareInn
provider_slug: kareinn
slug: kareinn-eligibility
source_date: '2026-11-09'
source_filename: kareinn-eligibility.yml
source_heading: Eligibility
source_page: https://kareinn.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KareInn\naid: kareinn\nurl: https://kareinn.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years old.\nrestricted_uses:\n- summary: Commercial endeavors restricted\n  text: The Site may not be used in connection with any commercial endeavors except those\
  \ that are specifically\n    endorsed or approved by us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Persons under the age of 18 are not permitted to use or register for the Site.\n"
source_yaml_url: https://artifacts.apis.io/kareinn/eligibility/kareinn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from KareInn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Care Homes
- Digital Care Planning
- Care Management
- Health
- Social Care
- CQC Compliance
- Software-as-a-Service
- United Kingdom
---
