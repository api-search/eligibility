---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The information contained on this website is provided for Australian residents only and is not being provided to any person who is a resident of any other country.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal-information solicitation
    text: You may not post or transmit, or cause to be posted or transmitted, any communication or solicitation designed or intended to obtain personal information from another user of this Website.
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
name: Mirvac
provenance_date: '2026-11-10'
provider_name: Mirvac
provider_slug: mirvac
slug: mirvac-eligibility
source_date: '2026-11-10'
source_filename: mirvac-eligibility.yml
source_heading: Eligibility
source_page: https://www.mirvac.com/conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mirvac\naid: mirvac\nurl: https://www.mirvac.com/conditions-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The information contained on this website is provided for Australian residents only and is not being provided\n    to any person who is a resident of any other country.\nentity_types: []\nrestricted_uses:\n- summary: No personal-information solicitation\n  text: You may not post or transmit, or cause to be posted or transmitted, any communication or solicitation designed\n    or intended to obtain personal information from another user of this Website.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mirvac/eligibility/mirvac-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Mirvac's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Property Development
- Property Management
- Funds Management
- Build-to-Rent
- Australia
---
