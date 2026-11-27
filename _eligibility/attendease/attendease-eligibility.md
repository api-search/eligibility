---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age, or the legal age of majority where you reside if that jurisdiction has an older age of majority, to register for an account.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age, or the legal age of majority where you reside if that jurisdiction has an older age of majority, to register for an account.
    value: '18'
  restricted_uses:
  - summary: No bot or automated account registration
    text: Accounts registered by “bots” or other automated methods are not permitted.
  - summary: No illegal or unauthorized use
    text: You may not use the Service for any illegal or unauthorized purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Attendease is not required to verify the actual identity or authority of a person using your Account or Credentials, but Attendease may in its discretion at any time require verification of the identity of a person seeking to access your Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Attendease
provenance_date: '2026-11-09'
provider_name: Attendease
provider_slug: attendease
slug: attendease-eligibility
source_date: '2026-11-09'
source_filename: attendease-eligibility.yml
source_heading: Eligibility
source_page: https://eventupplanner.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Attendease\naid: attendease\nurl: https://eventupplanner.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age, or the legal age of majority where you reside if that jurisdiction\n    has an older age of majority, to register for an account.\nrestricted_uses:\n- summary: No bot or automated account registration\n  text: Accounts registered by “bots” or other automated methods are not permitted.\n- summary: No illegal or unauthorized use\n  text: You may not use the Service for any illegal\
  \ or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Attendease is not required to verify the actual identity or authority of a person using your Account or\n    Credentials, but Attendease may in its discretion at any time require verification of the identity of a person\n    seeking to access your Account\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age, or the legal age of majority where you reside if that jurisdiction\n    has an older age of majority, to register for an account.\n"
source_yaml_url: https://artifacts.apis.io/attendease/eligibility/attendease-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Attendease's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Event
- Event Management
- Event Marketing
- Conferences
- Webinars
- Attendees
- Registration
- Software-as-a-Service
---
