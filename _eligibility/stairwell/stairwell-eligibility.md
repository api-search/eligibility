---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing and using the Site on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
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
name: Stairwell
provenance_date: '2026-11-10'
provider_name: Stairwell
provider_slug: stairwell
slug: stairwell-eligibility
source_date: '2026-11-10'
source_filename: stairwell-eligibility.yml
source_heading: Eligibility
source_page: https://stairwell.com/website-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stairwell\naid: stairwell\nurl: https://stairwell.com/website-terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing and using the Site on behalf of a company (such as your employer) or other legal entity,\n    you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stairwell/eligibility/stairwell-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Stairwell's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Threat Intelligence
- Malware Analysis
- Cybersecurity
- Threat Detection
- YARA
- Incident Response
---
