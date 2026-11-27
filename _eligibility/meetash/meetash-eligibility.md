---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Site is intended for users who are at least 18 years of age. All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Site.
    type: individual
  - text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No commercial endeavors without approval
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
name: MeetAsh
provenance_date: '2026-11-10'
provider_name: MeetAsh
provider_slug: meetash
slug: meetash-eligibility
source_date: '2026-11-10'
source_filename: meetash-eligibility.yml
source_heading: Eligibility
source_page: https://www.poweredbyash.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MeetAsh\naid: meetash\nurl: https://www.poweredbyash.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years of age. All users who are minors in the jurisdiction\n    in which they reside (generally under the age of 18) must have the permission of,\
  \ and be directly supervised\n    by, their parent or guardian to use the Site.\n- type: business\n  text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: No commercial endeavors without approval\n  text: The Site may not be used in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/meetash/eligibility/meetash-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from MeetAsh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Diagnostics
- At-Home Testing
- Lab Testing
- Digital Health
- Telehealth
- HIPAA
---
