---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You have the authority to enter into the Terms personally or on behalf of the entity that you represent
    type: business
  minimum_age:
    text: you are of legal age to form a binding contract with us
    value: null
  restricted_uses:
  - summary: No use violating law
    text: use this Site or its services (or any Site Content (as defined below)), in whole or in part, or submit any information to this Site, in violation of any applicable law, rule or regulation.
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
name: Earnest Research
provenance_date: '2026-11-09'
provider_name: Earnest Research
provider_slug: earnest-research
slug: earnest-research-eligibility
source_date: '2026-11-09'
source_filename: earnest-research-eligibility.yml
source_heading: Eligibility
source_page: https://www.earnestanalytics.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Earnest Research\naid: earnest-research\nurl: https://www.earnestanalytics.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You have the authority to enter into the Terms personally or on behalf of the entity that you represent\nrestricted_uses:\n- summary: No use violating law\n  text: use this Site or its services (or any Site Content (as defined below)), in whole or in part, or submit any\n    information to this Site, in violation of any applicable law, rule or regulation.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract with us\n"
source_yaml_url: https://artifacts.apis.io/earnest-research/eligibility/earnest-research-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Earnest Research's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Data
- Analytics
---
