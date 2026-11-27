---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Platform is controlled and offered by Safely from its facilities in the United States of America.
  entity_types:
  - text: a company or individual managing, distributing or marketing properties for rent
    type: business
  - text: you may not access or use the Services or accept the Terms of Service if you are not at least 18 years old
    type: individual
  minimum_age:
    text: you may not access or use the Services or accept the Terms of Service if you are not at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No booking without intent to stay
    text: request or book a stay at any Accommodation if you will not actually be staying at the Accommodation yourself
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
name: Safely
provenance_date: '2026-11-10'
provider_name: Safely
provider_slug: safely
slug: safely-eligibility
source_date: '2026-11-10'
source_filename: safely-eligibility.yml
source_heading: Eligibility
source_page: https://safely.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Safely\naid: safely\nurl: https://safely.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Platform is controlled and offered by Safely from its facilities in the United States of America.\nentity_types:\n- type: business\n  text: a company or individual managing, distributing or marketing properties for rent\n- type: individual\n  text: you may not access or use the Services or accept the Terms of Service if you are not at least 18 years old\nrestricted_uses:\n- summary: No booking without intent to stay\n  text: request or book a stay\
  \ at any Accommodation if you will not actually be staying at the Accommodation yourself\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you may not access or use the Services or accept the Terms of Service if you are not at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/safely/eligibility/safely-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Safely's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Short-Term Rental
- Vacation Rentals
- Guest Screening
- Travel Insurance
- Property Management
---
