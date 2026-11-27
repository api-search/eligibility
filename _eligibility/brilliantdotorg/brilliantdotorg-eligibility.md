---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service may not be accessed where prohibited by law, and any such right of access is revoked in those jurisdictions.
  entity_types:
  - text: User certifies to Brilliant that if User is an individual (i.e., not a corporation), User is legally permitted to use the Services
    type: individual
  - text: if User is an individual (i.e., not a corporation)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: User shall not use the Service or any Content for any purpose that is unlawful or prohibited by this Agreement, or that infringes the rights of Brilliant or others.
  - summary: Export restrictions
    text: User agrees not to import, export, re-export, or transfer, directly or indirectly, any part of the Service or any information provided on or pursuant to the Service except in full compliance with all United States, foreign and other applicable laws and regulations.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Brilliant reserves the right to take reasonable steps to verify age, identity, and parent/guardian consent, and to suspend or terminate access if such verification is not successful.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brilliantdotorg
provenance_date: '2026-11-09'
provider_name: Brilliantdotorg
provider_slug: brilliantdotorg
slug: brilliantdotorg-eligibility
source_date: '2026-11-09'
source_filename: brilliantdotorg-eligibility.yml
source_heading: Eligibility
source_page: https://brilliant.org/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brilliantdotorg\naid: brilliantdotorg\nurl: https://brilliant.org/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service may not be accessed where prohibited by law, and any such right of access is revoked in those\n    jurisdictions.\nentity_types:\n- type: individual\n  text: User certifies to Brilliant that if User is an individual (i.e., not a corporation), User is legally permitted\n    to use the Services\n- type: business\n  text: if User is an individual (i.e., not a corporation)\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: User shall\
  \ not use the Service or any Content for any purpose that is unlawful or prohibited by this Agreement,\n    or that infringes the rights of Brilliant or others.\n- summary: Export restrictions\n  text: User agrees not to import, export, re-export, or transfer, directly or indirectly, any part of the Service\n    or any information provided on or pursuant to the Service except in full compliance with all United States,\n    foreign and other applicable laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Brilliant reserves the right to take reasonable steps to verify age, identity, and parent/guardian consent,\n    and to suspend or terminate access if such verification is not successful.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brilliantdotorg/eligibility/brilliantdotorg-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Brilliantdotorg's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
