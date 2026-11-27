---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you have the authority to bind Client and its affiliates to the terms and conditions of this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No FCRA-covered purposes
    text: No service provided by DONORSEARCH shall, under any circumstance, be utilized for any purpose covered under the FCRA.
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
name: DonorSearch
provenance_date: '2026-11-09'
provider_name: DonorSearch
provider_slug: donorsearch
slug: donorsearch-eligibility
source_date: '2026-11-09'
source_filename: donorsearch-eligibility.yml
source_heading: Eligibility
source_page: https://www.donorsearch.net/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DonorSearch\naid: donorsearch\nurl: https://www.donorsearch.net/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You represent that you have the authority to bind Client and its affiliates to the terms and conditions\n    of this Agreement.\nrestricted_uses:\n- summary: No FCRA-covered purposes\n  text: No service provided by DONORSEARCH shall, under any circumstance, be utilized for any purpose covered under\n    the FCRA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/donorsearch/eligibility/donorsearch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from DonorSearch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Non-Profit
- Fundraising
- Donor Research
---
