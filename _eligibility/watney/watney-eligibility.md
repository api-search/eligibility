---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you represent that you are not located in, organized under the laws of, or ordinarily resident in an embargoed or sanctioned jurisdiction
  entity_types:
  - text: If you use the Site on behalf of a company or other organization, you represent that you are authorized to bind it, and "you" refers to that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: Use the Site in violation of any applicable law or regulation, or for any unlawful or fraudulent purpose;
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
name: Watney
provenance_date: '2026-11-10'
provider_name: Watney
provider_slug: watney
slug: watney-eligibility
source_date: '2026-11-10'
source_filename: watney-eligibility.yml
source_heading: Eligibility
source_page: https://watney.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Watney\naid: watney\nurl: https://watney.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you represent that you are not located in, organized under the laws of, or ordinarily resident in an embargoed\n    or sanctioned jurisdiction\nentity_types:\n- type: business\n  text: If you use the Site on behalf of a company or other organization, you represent that you are authorized\n    to bind it, and \"you\" refers to that organization.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: Use the Site in violation of any applicable law or regulation,\
  \ or for any unlawful or fraudulent purpose;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/watney/eligibility/watney-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Watney's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Artificial Intelligence
- Automation
- Space
---
