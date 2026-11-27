---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Only legal entity companies organi zed and registered in the United States (such as corporations and LLCs) and sole proprietors may apply for an AtoB Account and use the Services
  entity_types:
  - text: Only legal entity companies organi zed and registered in the United States (such as corporations and LLCs) and sole proprietors may apply
    type: business
  - text: Individual consumers, unincorporated partnerships, and companies organized and registered outside the United States are not permitted to attempt to open or to use an AtoB Account or the Services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal, family or household use
    text: Users may not use the Services for personal, family, or household purposes.
  - summary: Sanctioned parties or jurisdictions
    text: provided to or used for any Transaction involving an individual, organization, country, or jurisdiction that is blocked or sanctioned by the United States, including those identified on any lists maintained by the U.S. Treasury Department’s Office of Foreign Assets Control (OFAC)
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: We may approve or deny your application for an AtoB Account or grant you provisional access to the Services or a n AtoB Account while your application is pending additional review.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AtoB
provenance_date: '2026-11-09'
provider_name: AtoB
provider_slug: atob
slug: atob-eligibility
source_date: '2026-11-09'
source_filename: atob-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/62c496dceca674e60a6d1ecd/69dd29605b6d1df354f40136_AtoB%20Platform%20Agreement.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AtoB\naid: atob\nurl: https://cdn.prod.website-files.com/62c496dceca674e60a6d1ecd/69dd29605b6d1df354f40136_AtoB%20Platform%20Agreement.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Only legal entity companies organi zed and registered in the United States (such as corporations and LLCs)\n    and sole proprietors may apply for an AtoB Account and use the Services\nentity_types:\n- type: business\n  text: Only legal entity companies organi zed and registered in the United States (such as corporations and LLCs)\n    and sole proprietors may apply\n- type:\
  \ individual\n  text: Individual consumers, unincorporated partnerships, and companies organized and registered outside the United\n    States are not permitted to attempt to open or to use an AtoB Account or the Services.\nrestricted_uses:\n- summary: Personal, family or household use\n  text: Users may not use the Services for personal, family, or household purposes.\n- summary: Sanctioned parties or jurisdictions\n  text: provided to or used for any Transaction involving an individual, organization, country, or jurisdiction\n    that is blocked or sanctioned by the United States, including those identified on any lists maintained by the\n    U.S. Treasury Department’s Office of Foreign Assets Control (OFAC)\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: We may approve or deny your application for an AtoB Account or grant you provisional access to the Services\n    or a n AtoB Account while your application is pending additional review.\nminimum_age:\n \
  \ value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/atob/eligibility/atob-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from AtoB's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fleet Management
- Fuel Cards
- Payments
- Fintech
- Trucking
- Spend Management
- Commercial Cards
---
