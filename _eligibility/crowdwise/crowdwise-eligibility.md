---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company makes no representation that the Website is appropriate or available in other locations other than where it is operated by Company.
  minimum_age:
    text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) are not permitted to register for the Website or use the Company Services.
    value: '18'
  restricted_uses:
  - summary: Commercial endeavors restricted
    text: The Website may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by Company.
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
name: Crowdwise
provenance_date: '2026-11-09'
provider_name: Crowdwise
provider_slug: crowdwise
slug: crowdwise-eligibility
source_date: '2026-11-09'
source_filename: crowdwise-eligibility.yml
source_heading: Eligibility
source_page: https://crowdwise.org/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crowdwise\naid: crowdwise\nurl: https://crowdwise.org/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company makes no representation that the Website is appropriate or available in other locations other than\n    where it is operated by Company.\nentity_types: []\nrestricted_uses:\n- summary: Commercial endeavors restricted\n  text: The Website may not be used in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by Company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) are not\n    permitted to register for the Website or use the Company Services.\n"
source_yaml_url: https://artifacts.apis.io/crowdwise/eligibility/crowdwise-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Crowdwise's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Equity Crowdfunding
- Education
- Community
- Tools
---
