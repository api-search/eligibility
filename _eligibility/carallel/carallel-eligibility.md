---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Carallel Services are intended for use solely by and/or on behalf of individuals located in the United States who are age 18 and over.
  entity_types:
  - text: Services are intended for use solely by and/or on behalf of individuals located in the United States who are age 18 and over.
    type: individual
  minimum_age:
    text: Carallel requires all of Your Information be provided only by individuals 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Competitors and competitive monitoring
    text: 'Without our prior written consent, which may be withheld in our sole discretion, you may not accept this Agreement, accept our Services, or access the Digital Tools: (a) if you are our direct competitor; or (b) to monitor the Digital Tools or our Services for availability, functionality, features, performance or operation'
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
name: Carallel
provenance_date: '2026-11-09'
provider_name: Carallel
provider_slug: carallel
slug: carallel-eligibility
source_date: '2026-11-09'
source_filename: carallel-eligibility.yml
source_heading: Eligibility
source_page: https://carallel.com/terms-of-use-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carallel\naid: carallel\nurl: https://carallel.com/terms-of-use-agreement/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Carallel Services are intended for use solely by and/or on behalf of individuals located in the United States\n    who are age 18 and over.\nentity_types:\n- type: individual\n  text: Services are intended for use solely by and/or on behalf of individuals located in the United States who\n    are age 18 and over.\nrestricted_uses:\n- summary: Competitors and competitive monitoring\n  text: 'Without our prior written consent, which may be withheld in our\
  \ sole discretion, you may not accept this\n    Agreement, accept our Services, or access the Digital Tools: (a) if you are our direct competitor; or (b) to\n    monitor the Digital Tools or our Services for availability, functionality, features, performance or operation'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Carallel requires all of Your Information be provided only by individuals 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/carallel/eligibility/carallel-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Carallel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Caregiving
- Digital Health
- Platform
- B2B
---
