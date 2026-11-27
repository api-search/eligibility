---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are acting on behalf of your employer or another entity, you represent and warrant that you are authorized to bind such employer or entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Interference with or disruption of Sites
    text: Attempt to interfere with or disrupt the Sites or otherwise access the Sites or use the Content in violation of any applicable laws or regulations.
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
name: Maxima
provenance_date: '2026-11-10'
provider_name: Maxima
provider_slug: maxima
slug: maxima-eligibility
source_date: '2026-11-10'
source_filename: maxima-eligibility.yml
source_heading: Eligibility
source_page: https://www.maxima.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Maxima\naid: maxima\nurl: https://www.maxima.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are acting on behalf of your employer or another entity, you represent and warrant that you are authorized\n    to bind such employer or entity to these Terms.\nrestricted_uses:\n- summary: Interference with or disruption of Sites\n  text: Attempt to interfere with or disrupt the Sites or otherwise access the Sites or use the Content in violation\n    of any applicable laws or regulations.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/maxima/eligibility/maxima-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Maxima's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Accounting
- Financial Close
- Fintech
- Automation
- Enterprise
- Agents
---
