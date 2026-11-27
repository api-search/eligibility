---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Hostelworld Sites is not authorised in any jurisdiction that does not give effect to all provisions of these Terms
  entity_types:
  - text: you are 16 years of age or older in order to use the Hostelworld Sites and Hostelworld Services
    type: individual
  minimum_age:
    text: you are 16 years of age or older in order to use the Hostelworld Sites and Hostelworld Services.
    value: '16'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: Your use of the Hostelworld Sites and Hostelworld Services is permitted by Hostelworld only for personal, non-commercial use
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Hostelworld also reserve the right to take steps to verify your identity to process any booking request.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hostelworld
provenance_date: '2026-11-09'
provider_name: Hostelworld
provider_slug: hostelworld
slug: hostelworld-eligibility
source_date: '2026-11-09'
source_filename: hostelworld-eligibility.yml
source_heading: Eligibility
source_page: https://www.hostelworld.com/legal/hostel-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hostelworld\naid: hostelworld\nurl: https://www.hostelworld.com/legal/hostel-terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Hostelworld Sites is not authorised in any jurisdiction that does not give effect to all provisions\n    of these Terms\nentity_types:\n- type: individual\n  text: you are 16 years of age or older in order to use the Hostelworld Sites and Hostelworld Services\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: Your use of the Hostelworld Sites and Hostelworld Services is permitted by Hostelworld\
  \ only for personal,\n    non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Hostelworld also reserve the right to take steps to verify your identity to process any booking request.\nminimum_age:\n  value: '16'\n  text: you are 16 years of age or older in order to use the Hostelworld Sites and Hostelworld Services.\n"
source_yaml_url: https://artifacts.apis.io/hostelworld/eligibility/hostelworld-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Hostelworld's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Accommodation
- Booking
- Hospitality
---
