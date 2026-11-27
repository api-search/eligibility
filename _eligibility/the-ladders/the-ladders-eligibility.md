---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may only order Materials or Services if you are domiciled in the United States or Canada.
  entity_types:
  - text: Users must be at least the age of majority in the jurisdiction in which you reside in order to use the Site and the Services.
    type: individual
  - text: IF YOU ARE USING THE SITE FOR YOUR COMPANY’S USE, YOU REPRESENT THAT YOU ARE AN AUTHORIZED REPRESENTATIVE WHO HAS THE AUTHORITY TO LEGALLY BIND YOUR COMPANY TO THESE TERMS.
    type: business
  minimum_age:
    text: Users must be at least the age of majority in the jurisdiction in which you reside in order to use the Site and the Services.
    value: age of majority
  restricted_uses:
  - summary: Unauthorized activities
    text: You will not use our Site or Services if you are not eligible to use our Services in accordance with Section 2
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once you have submitted your account registration information, Ladders shall have the right to approve or reject the requested registration, in our sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: The Ladders
provenance_date: '2026-11-10'
provider_name: The Ladders
provider_slug: the-ladders
slug: the-ladders-eligibility
source_date: '2026-11-10'
source_filename: the-ladders-eligibility.yml
source_heading: Eligibility
source_page: https://www.theladders.com/corporate/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Ladders\naid: the-ladders\nurl: https://www.theladders.com/corporate/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may only order Materials or Services if you are domiciled in the United States or Canada.\nentity_types:\n- type: individual\n  text: Users must be at least the age of majority in the jurisdiction in which you reside in order to use the Site\n    and the Services.\n- type: business\n  text: IF YOU ARE USING THE SITE FOR YOUR COMPANY’S USE, YOU REPRESENT THAT YOU ARE AN AUTHORIZED REPRESENTATIVE\n    WHO HAS THE AUTHORITY TO LEGALLY\
  \ BIND YOUR COMPANY TO THESE TERMS.\nrestricted_uses:\n- summary: Unauthorized activities\n  text: You will not use our Site or Services if you are not eligible to use our Services in accordance with Section\n    2\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once you have submitted your account registration information, Ladders shall have the right to approve or\n    reject the requested registration, in our sole discretion.\nminimum_age:\n  value: age of majority\n  text: Users must be at least the age of majority in the jurisdiction in which you reside in order to use the Site\n    and the Services.\n"
source_yaml_url: https://artifacts.apis.io/the-ladders/eligibility/the-ladders-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from The Ladders's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Job
- Careers
- Recruiting
- Job Search
- Executive Jobs
- Employment
- Human Resources
---
